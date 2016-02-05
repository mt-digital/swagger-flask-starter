# Swagger Starter for Flask

The only reason it's "for Flask" is that the Javascript dependencies
live in `app/static/bower_components`. Eventually I'll put some
server- and client-generation logic in here.

For now, modify `api-spec.yaml` to create a new Swagger Spec for a new
API. Then run `./serve-swag.sh` and go to
[localhost:8000/swagger-ui/dist/?url=/api-spec.yaml](localhost:8000/swagger-ui/dist/?url=/api-spec.yaml)
to see your new spec!
