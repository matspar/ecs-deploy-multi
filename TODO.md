- Pass in a task definition as json (still needs a name)
- Pass in a task definition as a filename (still needs a name)
- Pass in AWS credentials are arguments
- Verify that boto3 reads AWS credentials from ENV
- Make -O (--only-if-modified) work for more than just updated container images, like:
    - Service configuration
    - Task configuration
- update_service
    - desiredCount
    - deploymentConfiguration.maximumPercent
    - deploymentConfiguration.minimumHealthyPercent
- Support specifying what configuration project to use (~/.aws/config)
