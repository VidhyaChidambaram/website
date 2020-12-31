# Apache Web Server set up

* Start docker
* run the following command :

```
docker run -dit --name vidhya-web -p 8080:80 -v /Users/vchidamb/Softwares/pet_projects/website/httpd/html:/usr/local/apache2/htdocs/ httpd:2.4
```

* docker ps (Observe webserver by name vidhya-web is now started)


### Bootstrap template

* Use any from startbootstrap.com (yes, the first google result)
