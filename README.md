# Jamming React App

A **React.js** App that allows users to search the Spotify library, 
create a custom playlist, then save it to their Spotify account.

## **Installation**

### **Register** your application using the [Spotify application registration flow](https://developer.spotify.com/my-applications/#!/applications).

Give your application a relevant *name* and *description*.\
Add the following Redirect URI:
http://localhost:3000/

### **Create React Environment Variables** for your application’s *client ID* and *redirect URI*.

Set the *client ID* variable to the value provided on your application page via Spotify.\
Set the *redirect URI* to [http://localhost:3000](http://localhost:3000)

`Example`:
```
# .env
REACT_APP_CLIENT_ID=api-value
REACT_APP_REDIRECT_URI=http://localhost:3000
```

## **Usage**

In the project directory, you can run:

```
npm start
```

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
