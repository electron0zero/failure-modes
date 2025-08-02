## failure-modes
Curated list of failures in software systems, and other literature around the same topic.

See [failuremodes.dev](https://failuremodes.dev) for more details

### Want to Help, or Questions, or concerns?

Ask us about it in our [WhatsApp Community](https://chat.whatsapp.com/IQOeAnHctWu2FSbgZ0Brro)

### Contributing

Contributions are welcome, to contribue:

1. follow Usage & Local Development section to setup local environment.
2. Create a new branch from `master` branch.
3. Create a new post (with `rake post`), and create a PR to `master` branch.
4. Once PR is merged, it will be deployed to [failuremodes.dev](https://failuremodes.dev) automatically.

### Usage & Local Development

This site is built using jekyll, so you need to install it to run it locally,
jekyll is based on Ruby so you need Ruby and Bundler installed on your system.

#### Prerequisites

1. Install RVM - [RVM Installation Guide](https://rvm.io/rvm/install)
2. Install Ruby using RVM - [Ruby Installation](https://rvm.io/rubies/installing)
3. Install Bundler - `gem install bundler`

Using Ruby 3 or higer is recommend and you can use any Ruby Version manager, RVM is not a hard requirement.

> NOTE: if `rvm install` fails, install openssl `brew install openssl@3` and give that path during install. example: `rvm install 3.3.7 --with-openssl-dir="$(brew --prefix openssl@3)"`

#### Development Setup

1. git clone
2. install gems `bundle install`
3. start local server with `rake` or `rake preview` or `jekyll server --trace` if don't have rake installed.
4. start local server with drafts `jekyll server --trace --drafts`
5. Build website `rake build` or `jekyll build --trace` if don't have rake installed.
6. Create a new post with `rake post "Title of post"`, it will create a new file in `_posts` directory with current date and title of post.
