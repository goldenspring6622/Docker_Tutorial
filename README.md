# Docker_Tutorial on Windows
cd to directory containing static HTML files and all theirs related folder.<br>
write Dockerfile :cmd -> echo Dockerfile <br>
write requirements.txt: cmd -> echo requirements.txt <br>
dockerize : <b>images -> container </b><br>
<b>images</b> : <br>
<code>docker build -t <NAME> .<OR a folder directory></code>
<b>container</b> : <br>
<code>docker run -p <8080:80 or any port> -d <IMAGE NAME></code>

