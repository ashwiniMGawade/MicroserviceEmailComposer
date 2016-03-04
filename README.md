# MicroserviceEmailComposer

This is the lambda function triggered with the new entry in the EmailComposer table.
which will give the call to the amazon aws api to fill in EmailSender table in dynamodb.

add .env file at the root of the directory with the following values


API_URL = "VALUE OF THE API URL"
MICROSERVICE_EMAIL_COMPOSER_ARN = "ARN_OF_THE_LAMBDA_FUNCTION"
