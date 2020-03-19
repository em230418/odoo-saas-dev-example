SaaS deploy example
===================

For developer perposes only!

How to use?
-----------
```
# clone repos somewhere
git clone https://github.com/em230418/saas-addons.git -b 13.0-saas-port
git clone https://github.com/OCA/queue.git -b 13.0
git clone https://github.com/OCA/web.git -b 13.0
```

and edit paths to these repos in docker-compose.yml

In my case I cloned repos above in:
```
~/Projects/c13/vendor/it-projects-llc/saas-addons
~/Projects/c13/vendor/OCA/web
~/Projects/c13/vendor/OCA/queue

```

and then open http://odoo.localhost
