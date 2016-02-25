# IonicApp


# What is Ionic?

	-- Ionic is an open source framework that is optimized for all things mobile.
	-- It enables you to build mobile apps using HTML5, Javascript, css.
	-- Ionic is built on top of angularjs app which means that all of your pre-existing angularjs knowedge.
	-- Ionic is especially built for Cordova apps.
	-- Ionic provides a framework like bootstrap, out of the box Javascript component and css.
	-- And it can easily be customized to meet your specific needs.
	-- Quick look at the Ionic website - http://ionicframework.com/
	-- Read details 1. http://ionicframework.com/docs/guide/preface.html 2. https://github.com/driftyco/ionic

# Cordova - what and why?

	-- Javascript API that "wraps" native app
		- Cordova, which was formally knows as PhoneGap, provides a javascript API that wraps native API such as the camera or geo location on the actual mobile device. Cordova is cross-platform. So, regardless of whether you're on android, ios or windows, cordova will ensure that you can write the code with a consistent API that can be reused everywhere.

	-- Native mobile apps using HTML/JS/CSS
		- Cordova enables you to build mobile apps that are natively installed via the app strore on each respected platform. So the apps are physically installed on the device just like every other native app. The defferences is cordova allows you to built these apps with HTML5,Javascript and css.

	-- Re-use existing web skill
		- Since cordova enables developers to use HTML and Javascript, this means we can reuse our existing web skills. 

	-- Re-use existing web framework
		- Not only can we leverage existing web skills but also existing web framework. There is no better example than the ionic framework is built on top of angularjs.All of your existing angualarjs knowledge will transfer when using the ionic framework in a cordova app.

	-- Quick look at the Cordova website - https://cordova.apache.org/

# Getting started with Ionic

	# Ionic command line features

		1. start : starts a new ionic project
		2. serve : starts a local development serve
		3. platform : configure platform target
		4. build : locally build app for a platform
		5. emulator : emulate app in simulator
		6. run : run app on device

	# Installing Ionic

		1. Before installing ionic, you must have NODEJS install in your machine
		2. From my command line prompt, install Ionic
				npm install ionic -g
		3. Install cordova
				npm install cordova -g

		With those two installations complete we are now ready to start using Ionic 
