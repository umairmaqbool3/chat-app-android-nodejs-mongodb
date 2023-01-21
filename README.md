# Android chat app - Kotlin, Node JS, Mongo DB

We created a chat application in native android using Kotlin, Node JS and Mongo DB.

# How to install

- Make sure you have downloaded and installed Node JS and Mongo DB in your system.

- Open command prompt or terminal inside "api" folder and run the following commands one-by-one:
	> npm update
	> npm install -g nodemon
	> nodemon server.js

- Run the following command:
	> ifconfig (mac, linux)
	or
	> ipconfig /all (windows, linux)

- And copy the ipv4 address, it will be something like this:
	> inet 192.168.8.101

- Copy the address after "inet"

- Paste it in "android/app/src/main/java/com/adnantech/chatapp_free_version/utils/MySharedPreference.kt" at line 12

- Also paste it in "api/server.js" variable named "global.apiURL"

If you need any help, feel free to contact us: support@adnan-tech.com