*Build Image:* <br />
docker build -t mmngt:0.4 . <br />   
<br />

*Run Image:* <br />
docker run -it -d -p 8082:5000 --name mmngt mmngt:0.3 <br />   
<br />

*deploy Image:* <br />
docker push mmngt:0.4 <br />   
<br />


