# awscodebuildproject1

AWS CodeBuild using the console

Steps

Step 1: Create two S3 buckets

Step 2: Create the source code

Step 3: Create the buildspec file

Step 4: Upload the source code and the buildspec file

Step 5: Create the build project

Step 6: Run the build

Step 7: View summarized build information

Step 8: View detailed build information

Step 9: Get the build output artifact

Step 10: Delete the S3 input bucket


CLI Commands:

aws codebuild create-project --generate-cli-skeleton

aws codebuild create-project --cli-input-json file://create-project.json

aws codebuild start-build --project-name project-name

aws codebuild batch-get-builds --ids id

