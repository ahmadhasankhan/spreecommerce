In most cases, the easiest way to install Rails is to take advantage of RubyGems:

$ gem install rails -v 4.0.1

$ gem install bundler

$ brew install imagemagick

$ gem install spree_cmd

$ rails _4.0.0_ new mystore

$ cd mystore

$ spree install --auto-accept


Note that this command will add the Spree dependencies to your gemfile. If you are using a custom build of Spree, or are bundling Spree from Github, you may want to use the rails generator provided by the spree gem instead:

bash $ rails generate spree:install

This will run the spree generator using the version of Spree you have defined in your Gemfile. Running spree install with a custom source or build will generate an error as your Gemfile will be amended to require different versions of Spree.


$ rails s
