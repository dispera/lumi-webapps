# lumi-webapps
![Flask](http://flask.pocoo.org/static/logo/flask.png "Flask")

Here we store our Flask applications

Usage
=====
Developers can update their apps on this repository,
and the go to the salt master and to /srv/webapps,
and do a git pull.

Then they can push to their minions with:
salt '*' state.apply blogaap
(where blogapp can be helloapp or any other app)
