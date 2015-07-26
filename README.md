docker-ruby
===========

A Docker container for Ruby with rbenv.

Set the ruby version in the `docker/install_ruby_version` file of a dependent
container. The Ruby build will happen when the dependent container is built.
