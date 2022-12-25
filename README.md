# AspNetMicroservices
AspNetMicroservices
<h3>🛸 MongoDB in Docker</h3>
<ul>
<li>
To Download
<p>> docker pull rtsp/mongosh </p>
</li>
<li>
To Run For Local PC Port
<b><p>>docker run -d -p [portNumber]:[portNumber] --name [containerName] [imageName]</p></b>
<p>>docker run -d -p 27017:27017 --name shopping-mongo rtsp/mongosh</p>
</li>
<li>
To See Logs
<p>> docker logs -f shopping-mongo </p>
</li>
<li>
Interactive Terminal - Bash Command
<p>> docker exec -it shopping-mongo /bin/bash </p>
  <hr>
  <b>If bash is not have, should run this codes: 
    <p>apt-get update</p>
    <p>apt-get install -y mongodb</p>
</b>
  <hr>
</li>
</ul>
