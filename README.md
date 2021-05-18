Pratik Jivanji
Liona Sadler

Lab 10:
========
Excercise One Questions:
What programming language was used in this tutorial?
  Node.js [JavaScript]
  
What were the keys and values in the hello-world sample test event template?
  statusCode: 200,
  body: JSON.stringify('Hello from Lambda!')
  
What can you use if you want to automate the creation and cleanup of lambda function, log groups and roles?
  Automate and cleanup through AWS CLI.
  
  Lambda > Functions page
    Actions > Delete
  Lambda > Logs page
    Actions > Delete log group(s)
  Lambda > Roles Page 
    Actions > Delete role(s)
  
Excercise Two Questions:
Which line in the function code tries to retrieve the content type of the object?
  line 17 => get the response to process (it contains the content type).
  line 18 => get the content type.

In the test event JSON, what information do you see about the S3 bucket?
  bucket name
  ownerIdentity
  arn

What information do you see in the Execution Results tab after running test?
  An error, since the bucket name and key weren't used
  After fixing:
  Reponse:
    bucket content type: "image/png"
  Logs:
    Start, end & report request IDs
  Request type:
    Request ID

