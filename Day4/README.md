Enable Versioning for S3 Bucket

Why :
Versioning preserves all versions of an object, providing protection against accidental deletions and overwrites

Implementation checklist :
Using the AWS Management Console
Sign in to the AWS Management Console and open the Amazon S3 console.
Select the S3 bucket for which you want to enable versioning.
Navigate to the Properties tab.
Locate the Bucket Versioning section and click Edit.
Select Enable to turn on versioning.
Click Save changes.

Key Note:
Once enabled, versioning cannot be fully disabled, only suspended. 
Suspending stops the creation of new versions, but existing versions remain.
Storage Costs: Each object version is stored independently and incurs storage costs.
