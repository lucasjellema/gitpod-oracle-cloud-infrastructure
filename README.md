# gitpod-oracle-cloud-infrastructure
Gitpod workspace for working with Oracle Cloud Infrastructure - including CLI, Fn, Terraform, VS Oracle DevTools

Once the workspace is up and running, the following components will have been installed:

* OCI CLI 
* Terraform with the OCI Provider for Terraform
* Fn Client and Fn Server (for serverless functions - locally and on OCI)
* VS Code extension Oracle DevTools

Before you can actually start working with Oracle Cloud Infrastructure, a little configuration is required.

The files *config* and *oci_api_key.pem* in directory *.oci* need to contain proper connection details for your OCI account. Please edit both files, provide the correct information. Then these two files config and oci_api_key.pem need to be copied to directory *~/.oci*. Please execute these commands in the terminal to perform that copy action:

```
mkdir ~/.oci
cp .oci/config  ~/.oci
cp .oci/oci_api_key.pem  ~/.oci
```
