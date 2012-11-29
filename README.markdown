
## Jekyll Tour

The purpose of this document is to get up to speed with maintaining the site. I tend to forget all these things when I haven't touched any of this for a while

### Install

The best way to install Jekyll is via RubyGems:

     gem install jekyll

Jekyll requires the gems directory_watcher, liquid, open4, maruku and classifier. These are automatically installed by the gem install command.


### Running Jekyll

Usually this is done through the jekyll executable, which is installed with the gem. In order to get a server up and running with your Jekyll site, run:

     jekyll --server

You'll also need the --auto option (provided either via command line parameters or the _config.yml) to watch files which change, if you plan to use the jekyll server during ongoing front-end development.

and then browse to http://0.0.0.0:4000. There's plenty of configuration options available to you as well.

On Debian or Ubuntu, you may need to add /var/lib/gems/1.8/bin/ to your path.

### Site structure

All generated files go in ./_site

The homepage is composed of ./index.html and the file in ./_layouts/default.html
All articles / posts will use another layout.


### Todo 

- Makefile for version updating and building the following
- js from google-closure-compiler
- css from sass files


#### links
http://stefanooldeman.github.com/
https://github.com/mojombo/jekyll/blob/master/README.textile
https://github.com/adinardi/google-closure-compiler
