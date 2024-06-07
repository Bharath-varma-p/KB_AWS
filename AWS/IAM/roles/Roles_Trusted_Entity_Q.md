# IAM Roles and Trusted Entities Quiz

## Question 1
What is a trusted entity in IAM roles?

<form>
  <input type="radio" name="q1" id="q1a" onclick="alert('Incorrect')">
  <label for="q1a">An IAM policy that grants permissions</label><br>
  
  <input type="radio" name="q1" id="q1b" onclick="alert('Correct!')">
  <label for="q1b">A specific user or service that is allowed to assume the role</label><br>
  
  <input type="radio" name="q1" id="q1c" onclick="alert('Incorrect')">
  <label for="q1c">A predefined AWS managed role</label><br>
  
  <input type="radio" name="q1" id="q1d" onclick="alert('Incorrect')">
  <label for="q1d">A group of users in IAM</label><br>
</form>

## Question 2
Which of the following is a valid trusted entity type?

<form>
  <input type="radio" name="q2" id="q2a" onclick="alert('Incorrect')">
  <label for="q2a">An AWS Lambda function</label><br>
  
  <input type="radio" name="q2" id="q2b" onclick="alert('Incorrect')">
  <label for="q2b">An IAM group</label><br>
  
  <input type="radio" name="q2" id="q2c" onclick="alert('Correct!')">
  <label for="q2c">Another IAM role</label><br>
  
  <input type="radio" name="q2" id="q2d" onclick="alert('Incorrect')">
  <label for="q2d">An EC2 instance</label><br>
</form>

## Question 3
What is the purpose of the trust policy in an IAM role?

<form>
  <input type="radio" name="q3" id="q3a" onclick="alert('Incorrect')">
  <label for="q3a">To define the permissions the role grants</label><br>
  
  <input type="radio" name="q3" id="q3b" onclick="alert('Incorrect')">
  <label for="q3b">To specify the AWS resources the role can access</label><br>
  
  <input type="radio" name="q3" id="q3c" onclick="alert('Correct!')">
  <label for="q3c">To define who can assume the role and under what conditions</label><br>
  
  <input type="radio" name="q3" id="q3d" onclick="alert('Incorrect')">
  <label for="q3d">To assign MFA requirements for the role</label><br>
</form>

## Question 4
Which statement is true about roles and trusted entities?

<form>
  <input type="radio" name="q4" id="q4a" onclick="alert('Incorrect')">
  <label for="q4a">Roles can only be assumed by users within the same AWS account</label><br>
  
  <input type="radio" name="q4" id="q4b" onclick="alert('Correct!')">
  <label for="q4b">Roles provide temporary security credentials to trusted entities</label><br>
  
  <input type="radio" name="q4" id="q4c" onclick="alert('Incorrect')">
  <label for="q4c">Roles must be attached to a specific EC2 instance</label><br>
  
  <input type="radio" name="q4" id="q4d" onclick="alert('Incorrect')">
  <label for="q4d">Roles cannot be assumed by AWS services</label><br>
</form>

## Question 5
How can you allow an EC2 instance to assume an IAM role?

<form>
  <input type="radio" name="q5" id="q5a" onclick="alert('Incorrect')">
  <label for="q5a">By adding the EC2 instance to an IAM group</label><br>
  
  <input type="radio" name="q5" id="q5b" onclick="alert('Correct!')">
  <label for="q5b">By creating a trust policy that specifies the EC2 service as the trusted entity</label><br>
  
  <input type="radio" name="q5" id="q5c" onclick="alert('Incorrect')">
  <label for="q5c">By directly attaching the role to the EC2 instance</label><br>
  
  <input type="radio" name="q5" id="q5d" onclick="alert('Incorrect')">
  <label for="q5d">By adding the EC2 instance to a VPC</label><br>
</form>
