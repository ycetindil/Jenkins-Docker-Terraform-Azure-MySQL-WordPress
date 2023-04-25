# WordPress Deployment on Azure Container Instance Using Jenkins

## Notes

- Create the Jenkins server.
- Manage Jenkins > Manage Credentials > System > Global credentials (unrestricted) > Add credentials > Secret text with the ID `DOCKER_HUB_TOKEN`.
- Create a pipeline with the name `wordpress`.