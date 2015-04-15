php5-nginx
==========

PHP5 w/nginx container for octohost.

To use an already built container:

`docker pull octohost/php5`

Or you can build it from [this source](https://github.com/octohost/php5):

`docker build -t your-organization/php5`


Push this repo to your octohost:

```
git clone https://github.com/octohost/php5-nginx.git
cd php5-nginx
git remote add octohost git@ip.address.here:php5-nginx.git
git push octohost master
```
