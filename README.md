# COPYRIGHT
  
 The following modified file does not belong to me, the original author is the user @tweakunwanted
 
 Link to the original work: https://github.com/tweakunwanted/OpenXC-Player
 
 
 # OpenXC-Player
 Open source web player compatible with XtreamCodes V2 API
 
 ### How to install
 
 Use a clean Ubuntu 18.04 (not running any other service or script will fail) and run the following:
 
 ```sh
 curl -s https://raw.githubusercontent.com/Jeremias0618/OpenXC-Player-master-Modifying/master/install.sh | sudo bash
 ```
 
 After that edit the file `/var/www/html/libs/config.php`
 
 ```
 // URL DNS
 define('IP','http://domain.com:80'); 
 ```
 
 Put your playlist DNS there!
 
 Access the web interface on http://IP
 
 Enjoy and don't forget to contribute back if this helped you :)
 
 #### Custom domain
 
 Edit `/etc/apache2/sites-available/000-default.conf` and add the following above "DocumentRoot":
 
 ```
 ServerName domain.com
 ```
 
### Screenshots

![image](https://steamuserimages-a.akamaihd.net/ugc/2485514623316959223/5FC7E3D5AF047256BBCA995BB4CADCC826278370/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false)

![image](https://steamuserimages-a.akamaihd.net/ugc/2485514623316959505/DD8DB5641452B55EEA23E3EB46E16BB8A7F263CA/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false)

![image](https://steamuserimages-a.akamaihd.net/ugc/2485514623316959884/4B15E5CE46F599C3F794B48722F9AB7FA494E5DA/?imw=5000&imh=5000&ima=fit&impolicy=Letterbox&imcolor=%23000000&letterbox=false)
