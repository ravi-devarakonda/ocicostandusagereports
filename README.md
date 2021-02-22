# OCI Cost & Usage reports 
## Pull OCI cost and usage reports via API using OCI Python SDK

### Prerequisites:
1. Python version 3.x installed
2. OCI Python SDK pre-installed. for instructions on installation and setting up OCI config file, please follow [this](https://oracle-cloud-infrastructure-python-sdk.readthedocs.io/en/latest/installation.html) document.
2. Create an IAM policy to endorse users in your tenancy to read cost reports from the OCI tenancy.<br> 
Example policy below. change `group_name` value from the below policy statement to the group you intend to provide access to.
```
define tenancy reporting as ocid1.tenancy.oc1..aaaaaaaaned4fkpkisbwjlr56u7cj63lf3wffbilvqknstgtvzub7vhqkggq
endorse group group_name to read objects in tenancy reporting
```


**Instructions**:
- Clone this repo
- modify only those lines in the code which has a comment `Update these values`
- run the script

