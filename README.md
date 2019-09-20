This is the GitHub repository for the Splurty web application project, completed for the University of Toronto Coding Bootcamp program.

<b>How to run the web application locally</b>
<HR>
<p>Be sure to have the vagrant and PuTTY installed.  You can find how to do that <a href="https://github.com/hashicorp/vagrant" target="_blank">here</a>.
  </p>
  
  <p>  
  * Clone the repository onto your computer.
  </p>
  
  <p>
  * Run the Command Prompt on your computer:
  
  ```cmd.exe```
  </p>

<p>
  * Start vagrant. (Change directory if you aren't already in the folder where vagrant lives by using `cd`.)<br />
  
  ```$ vagrant up```
  </p>
  
  <p>
  * Start PuTTY by entering Host Name and Port.<br />
  Enter login and password.
  </p>
  
  <p>
  * Once it loads and you see 
  
  ```[ENV]:/vagrant $```
  
  change your directory to the folder you saved the web application in.
  
  ```$ cd /vagrant/src/splurty```
  </p>
  
  <p>
  * Start up the application locally.<br />
  
  ```$ rails server -b 0.0.0.0 -p 3000```
  </p>
  
  <p>
  * Go to <a href="http://localhost:3030/">http://localhost:3030/</a>.
  </p>
