

Then create `src/Auth/auth0-variables.js`, which defines variables for Auth0 client.

```bash
$ touch src/Auth/auth0-variables.js
```

The inside of `auth0-variables.js` looks like this:
```javascript
export const AUTH_CONFIG = {
  domain: 'yourdomain.auth0.com',
  clientId: 'yourclientid',
  container: 'auth0-login-container'
}
```

And Finally,
```bash
$ yarn start
```
