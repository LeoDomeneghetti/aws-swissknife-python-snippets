# AWS SwissKnife Python Snippets

This project provides a set of snippets for creating code utilizing the AWS Python SDK **boto3**.

## Requirements
To install an extension you can run **Command Pallete** using the command Ctrl + Shift + P or Cmd + Shift + P, type Install Extensions and finally enter it, done that search for **AWS SwissKnife** and you will find the **Python Snippets** extension.

## Features
Utilizing this extension you can develop in a faster way, without the need to look in the **boto3** documentation all the time.

Start writing the service name followed by the action, you can press **⇥** to autocomplete with the snippet.

For example, if you would like to list the buckets in your AWS account:

![demo](images/extension-example.gif)

Some snippets examples (**⇥** is `TAB` key):

|             Prefix | Description                  |
|-------------------:|------------------------------|
|          `boto3 →` | Import the AWS SDK **boto3** |
|       `s3client →` | Create the **S3 client**     |
| `s3createbucket →` | Create a **S3 bucket**       |

## Release Notes
### 1.0.0
Initial release of aws-swissknife-python-snippets

## License Summary
This sample code is made available under the MIT-0 license. See the LICENSE file.
