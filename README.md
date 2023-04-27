<p>
<img src="https://i.imgur.com/Tx3uSba.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h1>AWS Cloud Computing Essentials - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites to migrate an existing website to static hosting on Amazon S3 in order to improve web application reliabiliy.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Create Amazon S3 Bucket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- AWS Account
- AWS Cloud Quest Membership

<h2>Operating Systems Used </h2>

- Amazon Web Services</b> 

<h2>List of Prerequisites</h2>

- Create an Amazon S3 Bucket.
- Enable static website hosting. 
- Secure the S3 bucket by using a bucket policy. 
- Rename Index.html to Waves.html. 


<h2>Disclaimer</h2>

<p>
<img src="https://i.imgur.com/uLMJIvN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Do not use your personal AWS account or any other accoun, or validation will fail and you might incure unexpected charges, this lab can be ran through AWS Cloud Quest system.
</p>
<br />

<p>
<img src="https://i.imgur.com/qSaTY3y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Use the search bar on the top of the AWS page type S3, and then click create.
</p>
<br />

<p>
<img src="https://i.imgur.com/qQAivBl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that you have created a new S3 bucket, you'll need to name it (remember the name), lab-unique-name-123, Select your AWS region on the dropdown, choose US East (N.Virginia) us-east-1. Scroll more and "ACLs Enabled", On Object ownership click object writer. Unclick "block all public access". Click the "I acknowledge the current setting button" Keep scroll and keep the rest of the options on the defaults. Now Click Create Bucket. 
</p>
<br />

<p>
<img src="https://i.imgur.com/LzousKK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The bucket has been created.
</p>
<br />

<p>
<img src="https://i.imgur.com/FIrOrA7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/p85exwv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Let's go ahead and upload a few files on the bucket. Click upload, In the files and folder section click add files. Choose the 4 files downloaded in the lab. index.html, main.js, styles.css, target-file.csv (Amazon s3 is like a data map between bucket + Key + version and the object itself. 
</p>
<br />

<p>
<img src="https://i.imgur.com/D7bNKGc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/kpP0q9F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
To Enable static website hosting. Click on the lab-unique-name-123 bucket and go to properties, once in the properites tab, scroll all the way down to "static website hosting and click the edit button. 
</p>
<br />

<p>
<img src="https://i.imgur.com/h6WZWyh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Enable "static website hosting, hosting type (Host a static website) and in the index document box, write "index.html. Amazon S3 supports two types of URL's virtual-hosted-style & Path-style. 
</p>
<br />

<p>
<img src="https://i.imgur.com/v9eViiz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To Secure the S3 bucket by using a bucket policy. Go back to the created bucket and click on permission, then edit "bucket policy". Copy the policy from the downloaded files that was added and paste it to the bucket policy section. Copy the ARN and paste it to the policy. Review to ensure that /* appears at the end of the ARN. Save Changes at the bottom of the screen. 
</p>
<br />

<p>
<img src="https://i.imgur.com/LkS4LVU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
<img src="https://i.imgur.com/bxrOjuW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Review to ensure the bucket hosting is set. Under Bucket website endpoin, Click the copy icon to copy the bucket website endpoint. Paste it in a new window. 
</p>
<br />

<p>
<img src="https://i.imgur.com/pskIaAy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Rename Index.html to Waves.html, select the index.html file, go to action, rename object, Change the object name to waves.html, Click Properties tab
Scroll down to the Static website hosting section and click Edit, Change the Index document to waves.html, Save changes.
</p>
<br />

<p>
<img src="https://i.imgur.com/A8rGdXZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


