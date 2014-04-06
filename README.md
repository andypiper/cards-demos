# Cards Demos

Using a Sinatra-based webserver, this project is serves content for practising building and using [Twitter Cards](http://dev.twitter.com/cards).

## Overview

This example uses:

- Ruby
- [Sinatra](http://www.sinatrarb.com/)
- [Bootstrap](http://twitter.github.com/bootstrap/) for visual sugar
- the rather nice [Github Fork Ribbon in CSS](http://simonwhitaker.github.com/github-fork-ribbon-css/) by [Simon Whitaker](htt://twitter.com/s1mn)
- Bower

## Deployment

Place web content (with an index.html file, and maybe a 404.html file) in the ``public`` folder, and either:

 * run ``bundle install`` then ``rackup`` from the root directory; or
 * deploy to Cloud Foundry.

... and you are good to go.

Optionally, fiddle with the settings in the top of the web.rb file to tweak how things work.

There is an example Cloud Foundry manifest.yml(.example) file - if you wish to use this for one-push deployment, rename to manifest.yml and edit the name of the application to be something unique for your Cloud Foundry installation, or the push will fail.
