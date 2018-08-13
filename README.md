# Heroku buildpack to remove node\_modules after build

Since Angular applications have no runtime dependency on _node\_modules_ after build, this buildpack removes this folder
to reduce slug size (significantly!). 
This results in a much faster dyno startup time.
