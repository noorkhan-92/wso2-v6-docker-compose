# WSO2 Identity Server with docker-compose.

This repository provides a docker-compose script for running and configuring WSO2-IS.

# How to Run?

- download `wso2is-6.0.0.zip` from [here](https://wso2.com/identity-server/) by clicking on 'Get Started'.
- place the downloaded file in the `wso2-is-docker-build` folder.
- the `deployment.toml` contains the configuration, make any changes you want.
- run `docker-compose up`. This command will build the container, mount the config folder and start the service passing through ports `9763` and `9443`

