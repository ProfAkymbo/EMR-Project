# EMR-Spark-Job PROJECT

## objectives

how to create an Amazon S3 bucket and an
IAM role using the AWS Management Console.
launching an Amazon EMR Serverless application

## Prerequisites

Before launching an Amazon EMR Serverless application, we need to create an S3 bucket to store output files and logs from the sample Spark Job we will be running.

Also, you will need an IAM role with an attached policy that grants permissions for Amazon EMR Serverless.
continue [here](https://docs.google.com/document/d/1J_RSPZp-_Wzn8pVQiRjd3UFOz7erkQHXETzzOeL7wmA/edit) with the detail steps.


Step 4
CLEAN UP

 To avoid incurring additional charges, it's important to complete this lesson in its entirety.

To get started, navigate to the AWS Management Console. In the search bar, enter EMR and select the EMR service option.

Next, from the left navigation pane, choose EMR Serverless.
Then, choose Manage applications.

Next, choose Applications from the left navigation pane. Then, select EMR tutorial. In the Action dropdown menu, choose Delete.

To confirm deletion, select the Delete permanently option, then Choose Delete application.

Now, delete the S3 bucket that you created. Proceed to the AWS Management Console. In the search bar, enter S3, and then choose the S3 option.

On the S3 Account snapshot screen, select the bucket you created, and then choose Empty.

Next, enter permanently delete in the text box to confirm, and then choose Empty.

Select the bucket again, and then choose Delete.

To confirm deletion, enter the name of the bucket in the text box, and then choose Delete bucket.

Next, delete the IAM policy created for the Amazon EMR Serverless job. Proceed to the AWS Management Console. In the search bar, enter IAM and select the IAM option.

From the IAM dashboard, choose Policies.

In the search bar, search for EMRServerlessS3AndGlueAccessPolicy.

Now, select the policy named EMRServerlessS3AndGlueAccessPolicy. In the Actions dropdown menu, choose Delete.

To confirm deletion, enter the policy name. Then, choose Delete.

Finally, delete the IAM role that you created for Amazon EMR Serverless job.

From the left navigation pane, choose Roles. Use the search bar and search for emrserverlessrole. Select the role, and then choose Delete.

To confirm the deletion, enter the role name. Then, choose Delete. You have successfully deleted AWS services created during this demonstration.

Resources -    https://github.com/johnny-chivers/emr-serverless
