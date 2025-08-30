# Back-Connect
***Simple back connect with bash***

*The tutorial is written in the file back-connect.txt*

<li>This method is one-time use and ends with connecting to nc (a feature of nc) , But you can run the program permanently with <b>'while'</b>.</li><br><br>In this method, two ports are opened in our system.<br>Port 8500 to specify commands and port 5600 to receive responses that do not pose a risk to your system.<br>Then the target that you have temporary access to also connects to your port 8500 with nc and receives the commands.<br>Then it sends the report to your port 8600.
