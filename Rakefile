# frozen_string_literal: true

# Rake tasks for Jekyll
require 'rake/clean'
require 'stringex'

# <\!--more--\> is excerpt_separator
DEFAULT_TEXT = "Add first paragraph here \n\n\<\!--more--\>\n\nAdd more content here".freeze
POSTS_DIR = '_posts'.freeze
BUILD_DIR = '_site'.freeze

CLEAN.include BUILD_DIR

desc 'Build the site'
task :build do
  sh 'jekyll', 'build', '--trace'
end

desc 'Start web server to preview site'
task :preview do
  sh 'jekyll', 'serve', '--watch', '--drafts', '--trace', '--port', ENV.fetch('PORT', '4000')
end

# Hacking Rake for pretty args
# exit at the end of task so rake can not execute our args as task
# https://stackoverflow.com/a/36929059

desc 'Create a new post, usage: rake post "Title of post" "Link to the incident details page"'
task :post do
  _, title, link = ARGV
  title ||= 'Title of new Post'
  link ||= 'Link to Incident details page'
  timestamp = Time.now.strftime('%Y-%m-%d')
  filepath = File.join(POSTS_DIR, "#{timestamp}-#{title.to_url}.md")
  build_file(filepath, title, link, timestamp)
  exit
end

task default: :preview

# create jekyll post file
def build_file(filepath, title, link, timestamp)
  File.open(filepath, 'w') do |f|
    f << "---\n"
    f << "layout: post\n"
    f << "title: \"#{title}\"\n"
    f << "date: #{timestamp || Time.now.strftime('%Y-%m-%d')}\n"
    f << "tags: ['New-Post', 'Tag']\n"
    f << "---\n"
    f << "\n"
    f << "[see more details](#{link})\n\n#{DEFAULT_TEXT}\n"
  end
  puts "Created: #{filepath}"
end

