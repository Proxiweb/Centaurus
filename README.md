#Centaurus

## The First Stellar Wallet for Android!

Stellar aims for the stars. And the nearest star system to us is Alpha Centauri!
The next step to get there is a functional app for sending and receiving payments.

The app is built using AngularJS, Cordova and the Ionic Framework. We first focus on android, but as Ionic is a platform agnostic tool, feel free to try it on the platform you like.

## Features

* Display account balances
* Send by manually pasting an address
* Send by scanning a QR-code
* QR-code for receiving
* Display recent transactions
* Encrypted backups

## Get it from [Google Play](https://play.google.com/store/apps/details?id=de.xcoins.centaurus)

## Contribute

I am a complete newbee to HTML/JS, Ionic, so 
* Use the app and report any bugs
* Just contribute new code
* Peer review and improve existing code
* Donate to our Stellar-Address `GAN65D2FEI63T4MBMOWWOP3K7VS6SVI5T6NNKIHNCI6PN32IGF6OVKSS`

## Levels of Contribution

There is a simple way for contribution as long as you don't develop on phone specific issues. 

While the simple mode is a good way to get started, you will soon want to see this on your own device. Or check the layout on several emulated devices or whatever.

### Simple 

* [Fork project](https://github.com/klopper/Centaurus) as usual.
* Open file './www/index.html' with your browser. What you see is close to what you have in the app.
* Modify the html views in './www/templates/' or the JS files in './www/js/'. Watch your changes immediatly by refreshing the page in the browser. 
* You might also want to add some JS libs to './www/lib/'.
* See [www/Readme.md](https://github.com/klopper/Centaurus/blob/master/www/README.md)

### Advanced (Android)

* We recommend VisualStudio Community Edition (free) and [Tools for Apache Cordova](taco.visualstudio.com/) (a.k.a. Taco)
  * Otherwise [Install Ionic](http://ionicframework.com/getting-started/). The [video tutorial for Windows users](http://learn.ionicframework.com/videos/windows-android/) is quite comprehensive
* [Fork project](https://github.com/klopper/Centaurus) as usual.
* make a copy of configTemplate.xml and name it config.xml
* Make sure your device is visible to your computer. You can check this by running ```adb devices```. More information coming soon.
* Navigate to your Centaurus root folder in the command line, use ionic to add android platform
* Build, deploy and run the app. Be Happy!
```bash
ionic platform android
ionic run android
```

### Advanced (other platforms)

No experience yet, so let us know.

## Links
* [Ionic](http://ionicframework.com/)
* [Stellar](https://www.stellar.org/blog/introducing-stellar/)
* ...
