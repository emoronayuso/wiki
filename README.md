Phusion Base Image 0.9.17 +MediaWiki-1.25.2 + nginx + PostgreSQL

**Build image:
  - Into directory of Dockerfile run:
  
        $ docker build -t emoronayuso/wiki .
  
  - Note: Change password posgres in Dockerfile before build image      
**Run container:

        $ docker run -e VIRTUAL_HOST="wiki.prueba.com" -p 80:80 -d -t emoronayuso/wiki

