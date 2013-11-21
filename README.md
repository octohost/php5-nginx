php5-nginx
==========

Base PHP5 w/nginx container for octohost.

To use an already built container:

`docker pull octohost/php5-nginx`

Or you can build it from this source:

`docker build -t your-organization/php5-nginx`


Push this repo to your octohost:

```
git clone https://github.com/octohost/php5-nginx.git
cd middleman
git remote add octohost git@ip.address.here:php5-nginx.git
git push octohost master
```

Example site \(usually\) at [http://php5-nginx.octohost.io](http://php5-nginx.octohost.io)
