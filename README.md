# template-net-core-webapi

Arquitecture hexagonal

* Authentication
* Fluent validation
* Swagger
* Fluent migrator
* MediatQR
* Adapter storage with amazon s3
* Adapter email with amazon ses


#For Credentials of Amazon AWS

you must create a user in amazon iam with the following permissions in s3, ses, sns. 
And add in the environment variables the following: AWS_ACCESS_KEY_ID / AWS_SECRET_ACCESS_KEY / AWS_SESSION_TOKEN
see the file WebApi\Properties\launchSettings.json