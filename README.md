# node-virtual-gamepads

This nodejs application provides the possibility to use your smarpthone as a gamepad controller
on Linux OS simply by reaching a local address.
You can virtually plug up to four gamepad controllers.

Demo
----
A video demo is available [here](https://www.youtube.com/watch?v=OWgWugNsF7w)

Prerequisite
------------
This application is only compatible with Linux OS with the **uinput** kernel module installed.

Installation
------------
    git clone https://github.com/miroof/node-virtual-gamepads
    cd node-virtual-gamepads
    npm install
    sudo node main.js

Usage
-----
Once the nodejs application is launched, you just have to plug your gamepad controller
by connecting your device on the same local network and by reaching the address *http://node_server_adress*

Features
--------

### Use it as standalone application (chrome mobile)
With the [add to homescreen](https://developer.chrome.com/multidevice/android/installtohomescreen) chrome feature,
you can easily use virtual gamepads application without launching the browser each time you want to play.

With only 3 clicks, virtual gamepads web application becomes a standalone application.

![Step 1](https://github.com/miroof/node-virtual-gamepads/blob/resources/screenshots/standalone_step1.png?raw=true)
![Step 1](https://github.com/miroof/node-virtual-gamepads/blob/resources/screenshots/standalone_step2.png?raw=true)

Then a shortcut is added on your homescreen and the application will be launched outside the browser.

![Step 1](https://github.com/miroof/node-virtual-gamepads/blob/resources/screenshots/standalone_step3.png?raw=true)
![Step 1](https://github.com/miroof/node-virtual-gamepads/blob/resources/screenshots/standalone_step4.png?raw=true)

### Enjoy haptic feedbacks

![Step 1](http://upload.wikimedia.org/wikipedia/commons/b/b8/GravitationalWave_CrossPolarization.gif)
