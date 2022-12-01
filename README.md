  Cloudformation example.
  This templates shows all options in a CloudFormation template to show what's possible.
  Solution deploys an S3 Bucket with Lambdas to manage files.
  Once a file is uploaded to "Source" bucket it is tagged and moved to "Processed" bucket in folders by year/month/day.
  Once a file is in "Processed" bucket an email is sent via SNS to you