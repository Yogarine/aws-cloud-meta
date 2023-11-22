# AWS Cloud meta-package

This meta-package can be used to limit AWS CDK versions to a specific version of
the Cloud Assembly Schema.

To use it, add it as a dependency to the `package.json` of your CDK project,
replacing the `aws-cdk`, `aws-cdk-lib`, `constructs` and `source-map-support` packages with
`aws-cloud-meta`. 
