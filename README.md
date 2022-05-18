# WSO2 MicroIntegrator DBS files

curl example
<pre>
#!/bin/sh

AUTH=api:heslo

# remove / insert / geometry
curl -u $AUTH http://IP:8290/services/postOBJEKTY/remove
curl -u $AUTH http://IP:8290/services/getOBJEKTY/get | curl -u $AUTH -H "Content-Type: application/xml"  -X POST http://IP:8290/services/postOBJEKTY/post -d @-
curl -u $AUTH http://IP:8290/services/postOBJEKTY/updatexy
curl -u $AUTH http://IP:8290/services/postOBJEKTY/url
</pre>
