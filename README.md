<h1>CI/CD Pipeline</h1>

<h2>Description</h2>
Created a CI/CD pipeline for a website with AWS and GitHub.
<br />

<h2>AWS Products Used</h2>

- <b>Simple Storage Service (S3)</b>
- <b>CodePipeline</b>

<h2>Other Services Used</h2>

- <b>GitHub</b>
- <b>w3scools.com</b>
- <b>imgur.com</b>

<h2>Project Stages:</h2>

<p align="center">
Created a GitHub repository to house the code: <br/>
<img src="https://imgur.com/aZmupA0.png" height="80%" width="80%" alt="cicd pipeline"/>
<br />
<br />
Using a website template from w3schools.com, edited the html and css. Inserted photos via Imgur:  <br/>
<img src="https://imgur.com/6KuXOUr.png" height="80%" width="80%" alt="cicd pipeline"/>
<br />
<br />
Set up S3 bucket to host static website, allowing access to the bucket and creating bucket policy: <br/>
<img src="https://imgur.com/CayoJgL.png" height="80%" width="80%" alt="cicd pipeline"/>
<br />
<br />
In AWS CodePipeline, linked Github account to AWS, allowing CodePipeline to have access to repository that houses the code:  <br/>
<img src="https://imgur.com/tWTBm8i.png" height="80%" width="80%" alt="cicd pipeline"/>
<br />
<br />
Tested the pipeline by inserting an additional photo within the index.html file in GitHub and checking that the file updated in the bucket. Execution history also showed successful pipeline and webiste ow displayed the new photo:  <br/>
<img src="https://imgur.com/C9uolBb.png" height="80%" width="80%" alt="cicd pipeline"/>
</p>
