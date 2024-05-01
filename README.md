
# Setup local environment For testing email flows MacOs

We are going to use Mailcatcher for this, follow the below practice to use this and forgot about mailtrap and other paid tools




## Step 1: Install Mailcatcher

Run this command

```bash
  brew install mailcatcher
```
## Step 2: Start the service

Once you are done with the installation and then you need to start the service by this command
```
  brew services start mailcatcher
```
## Step 3: Configure Env. variables in your application
(May be you need to update keys as per your app)
```
MAIL_MAILER=smtp
MAIL_HOST=localhost
MAIL_PORT=1025
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS="example@example.com"
MAIL_FROM_NAME="${APP_NAME}"
```
## Step 4: Access you local email
Open your web browser to http://localhost:1080. You should see all your email on this link.
## 🚀 About Me
I'm a full stack developer...
(inbox.hitendra@gmail.com)

