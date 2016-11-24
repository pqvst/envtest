# envtest

* deploy: `now --docker -d -f -e NODE_ENV=production`
* ensure NODE_ENV is set by visiting `/`
* crash it by visiting `/crash`
* wait for restart and check NODE_ENV by visiting `/`
