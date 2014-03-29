## Flint's Website

Totally awesome and responsive landing page for Flint, powered by middleman. 


## Middleman

We are using middleman as our static site generator to handle HAML & Sass compilation. 

If you arent famailair with middleman, I suggest you visit their [excellent docs](http://middlemanapp.com/basics/getting-started/) or read this swell [Tutorial](http://12devs.co.uk/articles/204/)

You need to install middleman and foundation_middleman

```
gem install middleman

wget http://cloud.travisstaton.com/foundation_middleman-0.0.1.gem
if you are paranoid (which is a good trait) you can check the md5 sum against 9f26c040f740c104042eb823e2071010
then run gem install on the downloaded file.
```

After installing a new gem managed by rbenv, you need to run 

```
rbenv rehash
```

This will generate the shims for any newly installed gems. 

## Clone this Repo

To clone this repo run

```
git clone git@github.com:FlintCo/website.git
```

then cd to that directory and run 

```
bundle install
bundle exec middleman server
```

You will seel the output from Middleman is now running locally, and you can visit it at [http://localhost:4567](http://localhost:4567)

To compile changes for production, you will need to open another terminal tab and type 

```
bundle exec middleman build
```

And viola. That should do it. 

