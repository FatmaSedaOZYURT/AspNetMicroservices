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
  <b>If bash is not have, should run this codes: </b>
    <p>apt-get update</p>
    <p>apt-get install -y mongodb</p>
  <br>*OR*</b>
  <p>docker exec -it shopping-mongo mongosh</p>
  <hr>
</li>
<li>
Create DB
<p>> mongo </p>
  <p>> use CatalogDb </p>
  <p>To create collection: > db.createCollection('Products') </p>
  <p><b>To Add Data:</b>
  <p>db.Products.insertMany([{'Name':'Asus Laptop','Category':'Computers', 'Summary':'Summary', 'Description':'Description', 'ImageFile':'ImageFile', 'Price':54.56},{'Name':'HP Laptop','Category':'Computers', 'Summary':'Summary', 'Description':'Description', 'ImageFile':'ImageFile', 'Price':66.56}])</p>
</p>
<p>To list data: > db.Products.find({}).pretty()</p>
<p>To delete datas: > db.Products.remove({})</p>
</li>
<li>
  <p>To Show DB: >show databases</p>
  <p>To Show Collections: >show collections</p>
  </li>
</ul>
