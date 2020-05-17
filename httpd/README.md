# Apache Web Server set up

* Start docker
* run the following command :

```
docker run -dit --name vidhya-web -p 8080:80 -v /Users/vchidamb/Softwares/pet_projects/website/httpd/html:/usr/local/apache2/htdocs/ httpd:2.4
```

* docker ps (Observe webserver by name vidhya-web is now started)


### Bootstrap template

#### Credits bootstrap template - StartBootstrap.com

My goal is to first master javascript stack, then the UX/UI, so reusing opensource CSS assets.

* startbootstrap.com (yes, the first google result)
