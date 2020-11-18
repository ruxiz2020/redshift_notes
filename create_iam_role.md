## Create an IAM Role

Here, you'll create an IAM role that you will later attach to your Redshift cluster to enable your cluster to load data from Amazon S3 buckets. Read more about IAM roles and Redshift here.

1. Sign in to the AWS Management Console and open the IAM console at https://console.aws.amazon.com/iam/.
2. In the left navigation pane, choose Roles.
3. Choose Create role.
<div>
<img src="img/iam1.png">
</div>
4. In the AWS Service group, choose Redshift.
5. Under Select your use case, choose Redshift - Customizable, and then Next: Permissions.
<div>
<img src="img/iam2.png">
</div>
6. On the Attach permissions policies page, choose AmazonS3ReadOnlyAccess, and then choose Next: Tags.
7. Skip this page and choose Next: Review.
<div>
<img src="img/iam3.png">
</div>
8. For Role name, enter `myRedshiftRole`, and then choose Create Role.
<div>
<img src="img/iam4.png">
</div>

You can now attach this role when you launch a new cluster or attach it to an existing cluster. In the next page, you'll attach the role to a new cluster.
