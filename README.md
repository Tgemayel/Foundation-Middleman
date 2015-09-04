## Foundation Middleman Boilerplate

![charles barkley](http://i.imgur.com/PCzlGBb.png)



This is a middleman template to get a static site up and running quickly with Foundation 5, Haml, Sass and Bower. Its a barebone template with all my default preferences. Some goodies this template provides:

* Middleman
* Foundation 5 
* Haml/Sass
* Bower 
* Livereload 
* Typekit 
* Google Analytics


## Usage 

Grab the template

```
$ git clone git://github.com/Tgemayel/Foundation-Middleman.git ~/.middleman/foundation
```

Create your project locally

```
# Optional - You can add this template for future use
$ middleman init [projectname] --template=foundation

```

Once you're project has been created, cd to that directory and grab the dependecies  


```
# install assets from bower
$ bower install    

# Install the gems 
$ bundle install

# Run the server 
$ bundle exec middleman server
```

Viola. You will see the output from Middleman now running locally at [http://localhost:4567](http://localhost:4567)



