# verify-vpcs-in-an-aws-region-from-an-existing-accounts-input-list
Requirements: aws-cli, and okta-cli installed and linux bash

# Create text file with list of accounts to parse, one on each line
We're using okta so we only care about aws account profiles that we created in okta

okta_aws --list > okta-profile-list.txt
We'll feed this list to our bash script. Edit as needed

Sample output:
