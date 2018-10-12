# LAN-Tube
LAN Tube is an Open Source Youtube like web app for your home network. 

![logo](https://user-images.githubusercontent.com/42372656/46865186-7a38a300-ce14-11e8-882a-1a6b790fd434.png)


Technologies

- Bootstrap 3
- PHP 5
- HTML 5
- MySQL

LAN Tube is an Open Source Youtube like web app for your home network. You can upload, watch videos online and download. All this on your local server no need for internet connection.
Please feel free do use the souce code to any purpose and please any contribution to the project will be highly welcomed


	Home page:

![ScreenShot](https://github.com/FotieMConstant/LAN-Tube/blob/master/screenshots/home.PNG)
 
	Upload section:

![ScreenShot](https://github.com/FotieMConstant/LAN-Tube/blob/master/screenshots/uploads.PNG)

LAN Tube is easy to install on your local server

How to install
- Extract the file on your local server folder. This is usually the 'www' OR 'htdocs' folder in your drive C:\
- Launch your local server. this can be any whether WAMP or XAMPP. Or any other
- Go to http://localhost/phpmyadmin
- Create database named 'lantub' on your local server.
- Import 'db.sql' from the databse folder.
	This will create a table named 'videos'. this table will collect 'id' of the video uploaded, the 'name' and the location of the file.
- Now all is almost done, just one thing left. We have to increase the maximum POST FILE SIZE and UPLOAD FILE SIZE. generally they are set by default to 8M and 2M for XAMPP respectively.
	
	- Look for the file 'php.ini' and increase the file size to the max you whish to have(E.g 2048MB). this file i generally found in 'C:\xampp\php' directory for XAMPP.
	- Once ther open the file and search for 'post_max_size' and 'upload_max_filesize'. You can now start editing.
- Launch the website and enjoy!





How to connect LAN Tube from another device.

- Connect the server computer on the same network as the other devices.
- On the server machine open comand prompt and type 'ipconfig' to get the ip address of the server computer.
- The ip address is IPv4 Address. . . . . . . . . . . : XXX.XXX.X.XXX.
- Use this ip on the other devices and you are set to go...

           ENJOY!!!
