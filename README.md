# FireBaseAuthDemo

In this project we will see how we can Authenticate with FireBase with Email and password and Google account.
for Achiving this you had first enable Email/Password and Google in FireBase | Authentication tab / sign in methods| .
1- sign-in and register with Email/Password is so simple and tehere is no need to config. just see the code.
2- for sign-in with Google you had to do like this:

 2.1. first you should created SHA1 debug key and add to **Firebase** console. creating SHA1 from [here][1].
 2.2. create both web api and android OAuth 2.0 client ID from [here][2]
 2.3. get generated `google-service.json` from **Firebase** console and put in app folder. 
 
  [1]: https://developers.google.com/android/guides/client-auth
  [2]: https://console.developers.google.com/projectselector/apis/credentials
