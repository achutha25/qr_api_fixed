I updated my GitHub Actions YAML file to run on pushes and pull requests to the master branch, ensuring that the CI/CD workflow was triggered automatically. I defined two distinct jobs: one to run Python tests with Pytest and another to build and push a Docker image to DockerHub. I set up a Python environment using the specified version and installed the necessary dependencies from the requirements file. I implemented caching for pip packages to expedite subsequent test runs. I configured the Docker build job for multi-platform builds by utilizing Docker Buildx and following proper building practices. I securely authenticated with DockerHub using GitHub secrets so that I could push the Docker image successfully. Finally, I added a step to scan the Docker image for vulnerabilities, which provided me with useful insights into potential security issues while executing the deployment pipeline.


## Testing QR codes on spec page

![openapi spec documentation page](images/img1.png)

