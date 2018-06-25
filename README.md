[![Build Status](https://travis-ci.com/bnc-projects/kinesis-data-preprocessor.svg?branch=master)](https://travis-ci.com/bnc-projects/kinesis-data-preprocessor)
# kinesis-data-preprocessor
## Prerequisite Steps
1. Create a build/deploy user for Travis CI
## Deployment Steps:
1. Run the role.yml cloudformation script
2. Use the AWS Credentials which were created for the build/deploy user in the .travis.yml file
3. Update the AWS region in the .travis.yml file to the approrpiate AWS region
