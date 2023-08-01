# Docker_Tutorial on Windows
cd to directory containing static HTML files and all theirs related folder.<br>
write Dockerfile :<code>cmd -> echo Dockerfile</code> <br>
write requirements.txt: <code>cmd -> echo requirements.txt </code><br>
dockerize : <b>images -> container </b><br>
<b>images</b> : <br>
<code>docker build -t < IMAGE_NAME> .<OR a folder directory></code><br>
<b>container</b> : <br>
<code>docker run -p <8080:80 or any port> -d < IMAGE_NAME></code>

