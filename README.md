<h1> <em> Server and Client in python</em> </h1>

Basic python script of a client and a server made in python using threads to make it work correctly. 

<h2> <em> Requirements </em> </h2>

Have python3 and Netcat installed

<h2> <em> Usage </em> </h2>

For the scripts to work correctly they must be executed as follows 
<pre>nc -h </pre>
<pre>nc -l -p 1234 -q 1 < server.py </pre>
In other terminal
<pre>nc localhost 1234 < client.py </pre>

