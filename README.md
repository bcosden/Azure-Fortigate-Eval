# Azure-Fortigate-Eval
Deploy a Fortigate to Azure that supports evaluation licenses from Fortinet

Starting with Fortigate 7.2.0, a free evaluation license can be used to play with a Fortigate in Azure.

To use the eval license, sign up for an account at Fortinet.com.

If you already have an account, ensure you do not already have an evaluation or trial license in your account. If you do, you will need to delete it or create a new account.

Then run deploy.sh from the Linux or WSL command line and enter parameters.

Once the deployment is complete, go to https://pubip address, log in using the credentials from the script, and then select evaluation license. Log in to Fortinet using your account to retrieve the eval license.

