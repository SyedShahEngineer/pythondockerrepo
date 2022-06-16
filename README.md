[![Board Status](https://dev.azure.com/kingshah0997/64c7d8cb-82e1-48ec-9891-1614084b8446/bb3fc6cd-570f-4e91-98a2-7bd5b02e0334/_apis/work/boardbadge/4c2d71c2-30d8-460c-b555-dac46c5908e2)](https://dev.azure.com/kingshah0997/64c7d8cb-82e1-48ec-9891-1614084b8446/_boards/board/t/bb3fc6cd-570f-4e91-98a2-7bd5b02e0334/Microsoft.RequirementCategory)
# myPythonDockerRepo
This a python based app and containerized.
you can clone - https://github.com/akannan1087/myPythonDockerRepo/.
This repo also have Jenkinsfile for automating the following:

- Automating Docker image creation
- Automating Docker image upload
- Automating Docker container provisioning

You can configure pipeline in your Jenkins instance(Docker also installed) by creating a Declarative pipeline.

Make sure you do the following:
1. Create Credentials for connecting to Docker registry
2. Create scripted pipeline using Jenkinsfile from this repo
3. Change registry per your user name = "your_username/mypython-app-may20"
4. Update your credentials ID in Pipeline you are creating.
5. Open port 8096 in Ec2 instance.
