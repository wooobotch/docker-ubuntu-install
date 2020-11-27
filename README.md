Installation script for Docker to run a specific stack (in this case redmine plus a database).

This aims to manage to check requierements, to download specific files (e.g.: dockerfiles, secrets)
and to deploy the whole project as services.
By commenting and uncommenting lines conveniently the installation will set either a docker-compose stack
or a group of containers, volumes and networks expected.

Some "echoes" will be moved to "cats" to the standard error output and some steps converted into functions
 as the code grows larger.
