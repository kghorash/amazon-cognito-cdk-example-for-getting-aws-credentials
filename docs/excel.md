# How to use excel with sts tokens
## Introduction

The purpose of this document is to outline steps required to connect Microsoft Excel to AWS Athena as a data source and utilize Excel as a BI tool to perform data analytics. 

## Create credentials file on laptop
Create the AWS credential files on the local computer.

•	Create directory c:\Users\<username>\.aws

•	Create a file with the name ‘credentials’ in this newly created directory

•	Add lines from below instructions to the ‘credentials’ file and save,

Login into: https://dp1luaobhtxif.cloudfront.net/

Click on “Access Keys” for either SdapDevAnalyst1, 2, or 3.
Under Option2 move the cursor to the highlighted area which changes to “Copy to Clipboard” with a black background. 
Click on “Copy to Clipboard” and paste values into the “credentials” file.

![option2](./images/option2-add-profile-to-aws-credentials.png)