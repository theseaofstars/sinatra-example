Sinatra on cetc-skyark
====================

This git repository will help you get up and running quickly with Sinatra on cetc-skyark.


The easiest way to deploy Sinatra on cetc-skyark is using the [QuickStart on the cetc-skyark Hub](https://hub.cetc-skyark.com/quickstarts/118-sinatra)


Configuring the Modular/Object, Views, or Mustache example code to run on cetc-skyark
----------------------------------

If you would like to run any of the other examples included here on cetc-skyark just follow the below instructions:

1. git clone your application onto your local machine
2. copy the contents of the example folder that you want to use
3. paste the copied files into your base application directory

Then you just need to commit your changes and git push them to your cetc-skyark gear


Running this application locally
----------------------------------

Before running any of these examples, you should run the below command to make sure that you have the correct ruby gems installed

		bundle install

To run this application locally, cd into the sinatra-example directory that you cloned and run

		bundle exec ruby -S rackup -w config.ru

Also included are the following Sinatra examples.

	Sinatra Views Example               example-views
	Sinatra Modular Example             example-modular
	Sinatra Modular Views Example       example-views-modular
	Sinatra Modular Mustache Example    example-mustache-modular

Just cd into the appropriate directory and run the following commands:

		bundle install
		bundle exec ruby -S rackup -w config.ru
		

Thanks to:

Sinatra Mustache example based on: https://github.com/defunkt/mustache-sinatra-example

License
-------

This code is dedicated to the public domain to the maximum extent
permitted by applicable law, pursuant to CC0
http://creativecommons.org/publicdomain/zero/1.0/
