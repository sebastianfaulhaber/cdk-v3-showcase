# cdk-v3-showcase
Resources for Red Hat Container Development Kit (CDK). More information on CDK can be found here: https://developers.redhat.com/products/cdk/overview/


## Install and enable additional addons

```
cd ./addons
minishift addon install custom-registry-console && minishift addon enable custom-registry-console
minishift addon install custom-import-container-images && minishift addon enable custom-import-container-images
minishift addon install custom-ci-cd
```