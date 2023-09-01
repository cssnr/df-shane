# Django Files Swarm Deploy

To deploy: [https://github.com/django-files/django-files](https://github.com/django-files/django-files)

## Variables and Secrets

You must have the following Variables and Secrets configured for your repository/org for this to work.

| Variable            | Type     | Description                                |
|---------------------|----------|--------------------------------------------|
| STACK_NAME          | Secret   | Name of Stack in Docker                    |
| CONFIG_FILE         | Secret   | Location of Config file in Service Configs |
| SERVICE_CONFIGS_KEY | Variable | SSH Key for Service Configs repo           |
| DOCKER_SSH_KEY      | Variable | Docker SSH Key                             |
| DOCKER_HOST         | Variable | Docker Hostname                            |
| DOCKER_USER         | Variable | Docker Username                            |
| DOCKER_PORT         | Variable | Docker Port                                |

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
