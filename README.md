# Brunch_Sass_Jade_Boilerplate

First boilerplate orientated to use modules of HTML and CSS. 

Include some libraries like jQuery, Bootstrap and TweenMax (GSAP).


## Getting to know Brunch

* Install (if you don't have them):
    * [Node.js](http://nodejs.org): `brew install node` on OS X
    * [Brunch](http://brunch.io): `npm install -g brunch`
    * Brunch plugins and app dependencies: `npm install`
* Learn:
    * `public/` dir is fully auto-generated and served by HTTP server.  Write your code in `app/` dir.
    * Place static files you want to be copied from `app/assets/` to `public/`.
    * [Brunch site](http://brunch.io), [Getting started guide](https://github.com/brunch/brunch-guide#readme)


## Installation of this repo

1. Clone this repo in your dev environment, you can simply run:
```console
foo@bar:~$ git clone https://github.com/AndrewAlva/Brunch_Sass_Jade_Boilerplate.git
```

2. Then install node modules through npm:
```console
foo@bar:~$ npm install
```

3. After that, you can run this code to get the final assets for production:
```console
foo@bar:~$ brunch build --production
```

This builds minified files for production

And that's it; now you are able to work on this repo.