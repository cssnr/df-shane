# Django Files Swarm Deploy

> **Note**
>
> This repository is designed to be forked and kept up to date.
> 
> DO NOT MODIFY FILES IN THIS REPOSITORY.
> 
> Everything is configured through Actions Variables and Secrets.

To deploy: [https://github.com/django-files/django-files](https://github.com/django-files/django-files)

## Variables and Secrets

You must have the following Variables and Secrets configured for your repository/org for this to work.

| Variable            | Type     | Description                                |
|---------------------|----------|--------------------------------------------|
| STACK_NAME          | Variable | Name of Stack in Docker                    |
| CONFIG_FILE         | Variable | Location of Config file in Service Configs |
| SERVICE_CONFIGS_KEY | Secret   | SSH Key for Service Configs repo           |
| DOCKER_SSH_KEY      | Secret   | Docker SSH Key                             |
| DOCKER_HOST         | Secret   | Docker Hostname                            |
| DOCKER_USER         | Secret   | Docker Username                            |
| DOCKER_PORT         | Secret   | Docker Port                                |

### Setup

1. Fork Repository
2. Add Variables and Secrets

### Deploy

- Go to the Repository
- Click on Actions Tab
- Select Docker Stack Deploy
- Click Run workflow
- Enter a different version if desired
- Click Run workflow
