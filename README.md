# s3-maven-repo-example
This repository accompanies a blog post detailing how to set up and use an S3-based Maven repository with Gradle. For more information see [that post](https://medium.com/@JacobASeverson/lean-artifact-repositories-1cea3442521b#.ulx4cwxxk)


# Creating the S3 Bucket

$ ./gradlew :artifact-repo:create

# Create S3 policy

./gradlew :artifact-repo:setBucketPolicy


# publish artifact into S3 - Publishing to the Repo

$ ./gradlew :player-api:publish


