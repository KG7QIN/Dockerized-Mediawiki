Bassed on the Docker Mediawiki Server instructions located at https://wiki.kg7qin.org/index.php/Docker_MediaWiki_Server

This repo includes the basic files to start your own Dockerized Mediwiki server

To get started:

### 1. Clone this repository
```
git clone
```
### 2. Download download the correct versions of the CirrusSearch and Elastic extensions and place in the build/extensions folder
CirrusSearch: https://www.mediawiki.org/wiki/Extension:CirrusSearch

Elastica: https://www.mediawiki.org/wiki/Extension:Elastica

### 3. Follow the instructions at the link above to setup this and the required NGINX proxy container to use.

Note: Make sure you change the environment variables for VIRTUAL_HOST, HTTPS_METHOD, LETSENCRYPT_HOST, and LETSENCRYPT_EMAIL to valid values for public (Internet) facing sites.  For private sites, remove or comment out these values.
 
