# Covid census
<h2>To setup Covidcensus you need to have downloaded the following</h2>
<h3>-XAMPP
	  -Any broswer of your choice
	  -visual studio code and extensions (html, php, jquery, javascript,css) (for futher developement)
	  -covid sensus project zip
  </h3>
	
<p>To download xampp here's a link : <a href="https://www.apachefriends.org/download.html"> Xampp</a></p>
<p>To download visual studio code here's a link :  <a href="https://code.visualstudio.com/download"> Visual Studio</a></p>
<p>Unzip the covidcensus.zip and transfer the covidsesnsus.sql file to a new location of your choice eg desktop</p>
	
<p>After downloading and installing the above you now move on to setting it up <br>
	-After installing xampp for linux users: <br>
							-first you open your file explorer and click on other locations <br>
							-then you click on computer <br>
							-then you click on opt <br>
							-next you click on lampp <br>
							-next you click on htdocs <br>
							-now once your in htdocs you need to copy and paste the covidcensus file in htdocs but since 
							 since your in user mode you dont have access so in other to transfer it you right click and 
							 open htdocs in the terminal and type 'pwd' and hit enter after which you copy the path you obtain. <br>
							-Next you go the folder where the extracted covidsensus project is for example downloads
							 you right click and open downloads in the terminal and type the following command 
							 'sudo cp -r foldername/filename address_of_destination_directory' i.e 'sudo cp -r covidcensus /opt/lampp/htdocs' and after you hit enter                  once that's complete you close htdocs. <br>
							-Next you open up the covidcensus.sql file in the desktop and then you open it up <br>
							-Next you open the terminal and type the following command to start xampp 'sudo /opt/lampp/lampp start' and hit enter after which you move                to your defualt browser and type 'localhost' and hit enter you will greeted with a welcome to Xampp page then you click phpMyadmin and you                click on the tab called 'sql'. <br>
							-You then return to the opened covidcensus.sql file and copy its contents and come and paste 
							 in the opened sql editor in your browser after pasting it you then click the 'Go' button 
							 to create the database for the project. <br>
							-Once this is done you then open a new tab in your browser and you type 'localhost/covidcensus/' and the website has been setup on your                    linux system. <br>
  </p>
  <pre>
  
  <img src="https://phil.cdc.gov//PHIL_Images/21074/21074_lores.jpg"  style="width:900px; height:400px;"  alt="covid">
  
  
  </pre>
  <p>
	-After installing xampp for windows users:
							-you open up local disk c or your windows partition and locate your xampp folder  then you
							 copy the covidcensus project folder and place in the xampp folder. <br>
							-next you open the covidcensus.sql file. <br>
							-Then you click on start and startup apache and mysql. <br>
							-you then type in your default browser 'localhost' and hit enter you will greeted with a welcome to Xampp page then you click phpMyadmin                  and you click on the tab called 'sql'. <br>
							-You then return to the opened covidcensus.sql file and copy its contents and come and paste 
							 in the opened sql editor in your browser after pasting it you then click the 'Go' button 
							 to create the database for the project. <br>
							-Once this is done you then open a new tab in your browser and you type 'localhost/covidcensus/' and the website has been setup on your                    linux system. </p>

<pre>

</pre>
<p>For developers after installing xampp and setting up your visual code or editor of preference you then follow the instruction above and setup the website based on the system you use for development. Finally you open the project file in your editor and begin your developement.</p>

<p>Please respect the website and used it only for the desisgned purposed and that is to inform the population covid 19. unix io:::ed </p>


	
