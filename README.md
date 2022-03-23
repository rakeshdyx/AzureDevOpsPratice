# AzureDevOpsPratice


## CI/CD in Azure DevOps

**CI/CD Pipeline**
Executes the continuous Integration process
Run the tasks or plans when code submitted(May be automatic or manual)
Uses a build agent
Create Build Artifacts

**Build and Agents**
Two type of pipeline
	- Build Pipeline
		- From source code checkout to Artifact publish as release  
	- Release Pipeline
		- From the release to Artifact deployment.
		
		
**Note:** 
YAML -
YAML is a human readable data serialization standard, often used to write configuration files.

Serialization - translates data structure or object state into format that can be stored and reconstructed later in a different computer environment.

 
**Create a Build pipeline**
Azure pipeline allows us to use `Config as code`  approach. 
Build Pipeline can be created in two ways -
	- Click for new build pipeline 
	- Import a pipeline - If you already have a pipeline in Jenkins or Bamboo, you can use the json file to import same pipeline.
TBD: Does Bamboo pipeline job allow to download a json file? Need to test it


