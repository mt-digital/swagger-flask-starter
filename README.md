# Swagger Starter for Flask

The only reason it's "for Flask" is that the Javascript dependencies
live in `app/static/bower_components`. Eventually I'll put some
server- and client-generation logic in here.

To install `swagger-ui` run `bower install` from the root repository directory. If you don't have `bower`, you first need `node.js` and the node package manager, `npm`.

For now, modify `api-spec.yaml` to create a new Swagger Spec for a new
API. Then run `./serve-swag.sh` and go to
[localhost:8000/swagger-ui/dist/?url=/api-spec.yaml](http://localhost:8000/swagger-ui/dist/?url=/api-spec.yaml)
to see your new spec!
