# HTTP Proxy


## test
* Run your script in pycharm or terminal</li>

* Open telnet in another terminal window so you can test the communication between the telnet and your script</p>
<b>N.B.</b>  ```18888``` is the number we used in the ```proxy_port_number = get_arg(1, 18888``` so if you changed it the script you should then change it in the previous command

* Write a request to test
```
telnet localhost 18888
```
Example:
```
GET http://eng.alexu.edu.eg/ HTTP/1.0\r\n\r\n
```
<b>N.B.</b> You should get a response of the source code of the the page your requested in the telnet terminal 


