# UploadNewLambdaVersion
A bash script to automatically delete an old lambda zip file, create a new one with updated code, and upload it aws lambda.

<h1>Installation and Use</h1>
<ol>
  <li>Download and install aws cli.</li>
  <li>Configure the aws cli with your AWS account details.</li>
  <li>Place the script file in the root directory along with the function dependencies and the the function itself.</li>
   <li>Edit the file, replacing all the terms below with details specific to your lambda function.</li>
   <li>CD into the root directory and run the script.</li>
</ol>


<h1>Requirements</h1>
<a href="https://aws.amazon.com/cli/">AWS cli</a>

<h1>Term Explanation</h1>
<ul>
<li>"OldZipFile.zip" - The name of the old zip file to be removed and replaced with the new one.</li>
<li>"NewZipFile.zip" - The name of zip file to be created and uploaded to aws.</li>
<li>"LambdaFunctionName" - The name of the lambda function being updated on aws.</li>
<li>"aws-region" - The aws region to upload to.</li>
</ul>
