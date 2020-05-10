# Apache Web Server set up

* Start docker
* run the following command :

```
docker run -dit --name vidhya-web -p 8080:80 -v /Users/vchidamb/pet_projects/website/httpd/html:/usr/local/apache2/htdocs/ httpd:2.4
```

* docker ps (Observe webserver by name vidhya-web is now started)

##### Okay, you can ignore this - this refers to the docker instance # to reuse next time

* docker start ea9

