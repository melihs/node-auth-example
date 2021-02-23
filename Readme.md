Setting up a simple authentication structure using the OpenID Connect  library

  
  

### Installation (Manual)

  

### Configure Auth0

You will need to register your application with Auth0 in order to start authenticating users. Go to the Applications screen in the Auth0 dashboard, create a new Regular Web Application, and follow the steps below.

  

**1. **Configure Callback URL****

A callback URL is an application route where Auth0 redirects users after they have authenticated. This URL must be registered with Auth0 or else users will be unable to log in to the application and will get a "Callback URL mismatch" error.

  

The callback URL for the application created in this quickstart is http://localhost:3000/callback. Paste that in the Allowed Callback URLs field for the application you just created.

  

**2. Configure Logout URL**

A logout URL is an application route that Auth0 can return users to after logging out. This URL must be registered with Auth0 or else users will be unable to log out of the application and will get a "misconfiguration" error.

  

The logout URL for the application created in this quickstart is http://localhost:3000. Paste that in the Allowed Logout URLs field for the application you just created, then scroll down and click Save Changes.

  

**3. Get Your Application Keys**

Finally, copy the following fields for your app in the env file

Domain, Client ID

    $ git clone
    $ npm i
    $ npm start
    $ localhost:3000/login
         
