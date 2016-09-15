# Module1 small project #
This projects is intended to be the "Hello, World!" of [Hexo](https://hexo.io/)
on [Heroku](https://www.heroku.com/)

## Task 1: Install Hexo ##
We are going to start simple and get Hexo working locally first.

1. We are going to need `npm`, the NodeJS package manger. If you are on Mac or
   Linux you can check if you already have it installed by running:

   ```
   > which npm
   >
   ```

   If you don't get anything back then it isn't installed. To get it we will
   need to install NodeJS and then `npm`. Mac and Windows users can use the
   [installers provided by NodeJS](https://nodejs.org/en/download/). Linux
   users can run:

   ```
   > sudo apt-get update
   > sudo apt-get install nodejs
   > sudo apt-get install npm
   ```

2. Install hexo.

   ```
   > npm install hexo-cli -g
   ```

## Task 2: local ##
### The basic website ###
   Now that you have Hexo installed, use it to build a basic website. Our only
   requirements at the moment are that your site should have a "page" and a
   "post". We will make it a bit more complicated later. Digitial Ocean has a
   [nice tutorial](https://www.digitalocean.com/community/tutorials/how-to-create-a-blog-with-hexo-on-ubuntu-14-04)
   on how you might do this (the relevant stuff starts at
   `hexo init ~/hexo_blog` midway through step 1 and stops after step 4).

### The fancy website ###
   In progress.



## Task 3: remote ##
Now that we have something that works locally, let's try to put it on Heroku.

1. [Deploy](https://hexo.io/docs/deployment.html#Heroku)

## Task 4: custom theme ##

put a [Hexo](https://hexo.io/) site up on [Heroku](https://www.heroku.com/)
site should have a "page" and a "post"
use a custom theme (maybe https://github.com/cgmartin/hexo-theme-bootstrap-blog)
(maybe) include a data file and loop through it to generate content
https://www.sitepoint.com/10-example-json-files/
https://github.com/jdorfman/awesome-json-datasets
https://api.github.com/emojis
(maybe) one or more additional requirements to exercise hexo functionality?
