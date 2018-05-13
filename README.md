# Athena
This is the repository for our project
the following files contain the code for the lambda functions in our project:

LambdaForLexandUI contains the code we used to communicate to the AWS Lex.
LambdaForLex is the code in the lambda function code hook that contains all the user input validations and the code to push user data to dynamo DB.
The other two files are triggered by cloudwatch to send out notifications through email to the user.

