# CloudFormation Templates by Avishay

Here is the work done for CloudFormation Templates on CyberArk

### Prerequisites

AWS CLI initialized on the command line

## Running The Templates

The `create-template.bat` file accept 2 arguments: template, and parameters.
Both parameters should be JSON files.

The template will be created as a ChangeSet with a Random name for the ChangeSet and the Stack, so you should check out CloudFormation to see what is going to be the stack name.

```
cd cli
.\create-template.bat Vault-Single-Deployment vault-sd-parameters
```

## Authors

* **Avishay Bar** - [avishayil](https://github.com/avishayil)