# AWS-IAM-Tutorial
Tutorial to create groups of AWS users with different access rights and a id/password authentification method

* Go to the [Identity and Access Management page](https://console.aws.amazon.com/iam/home) (connect to your AWS account)

### Groups
* To create a new group
    * Go to the group page ("group" button on the left)
    * Click on the "create new group" button : you will be able to choose a name and policies.
    * To select policies, don't forget to use the filter field. You can easily see the policies related to "EC2" for example

### Users
* To create a new user
    * Go to the user page ("user" button on the left)
    * Name the user(s) you want to create
    * Uncheck the "Generate an access key for each user" option


* You can easily add users in a group from the user page or from the group page
### User Authentification

* You can set a password for a user from its "Security Credentials" tab, "manage passwords" button


* User authentification
    * From the  [home of the IAM service](https://console.aws.amazon.com/iam/home), use the link "IAM users sign-in link" (top of the screen)
    * AWS will ask you a username and a password 
