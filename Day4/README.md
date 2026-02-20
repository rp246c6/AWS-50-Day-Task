Enable Versioning for S3 Bucket

Why :
Versioning preserves all versions of an object, providing protection against accidental deletions and overwrites

Implementation checklist :
1) Using the AWS Management Console
2) Sign in to the AWS Management Console and open the Amazon S3 console.
3) Select the S3 bucket for which you want to enable versioning.
4) Navigate to the Properties tab.
5) Locate the Bucket Versioning section and click Edit.
6) Select Enable to turn on versioning.
7) Click Save changes.

Key Note:
Once enabled, versioning cannot be fully disabled, only suspended. 
Suspending stops the creation of new versions, but existing versions remain.
Storage Costs: Each object version is stored independently and incurs storage costs.
