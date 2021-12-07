# Setup

- Run `git submodule update -init` to clone down the devenv repo.
- Run `git submodule update --remote` to checkout the latest commit in the devenv repo, so you get the latest scripts and images.
- Make a copy of `project.json.dist` into `project.json` and fill out your project's information.
- Run `./init` if this is the first time using this repo.
- For subsequent uses, run `./up` to bring up the containers.
- Check the `code` directory for any README files to setup that specific project.

**Other helpful commands:**

`./connect <name>` will connect to the docker container specified, or the project's `web` container by default.

`./stop` will bring down all the project containers.

`./destroy` will bring down and delete all the project containers and networks.
