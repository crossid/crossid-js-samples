# auth

This sample demonstrates how to _signup_, _signin_, _signout_ and show authenticated _user profile_ in vanilla Javascript SPA application.

The code runs on the browser and no backend is required.

## Setup

Edit `index.html` and specify _domain_, _clientId_ and _redirectUri_ according to your tenant and application configuration.

```javascript
const domain = '...'
const clientId = '...'
const redirectUri = '...'
```

Run the sample via docker:

```bash
docker run --rm -it -p 3000:80 $(docker build -q .)
```

This starts a temporary container with nginx that serves the files statically, open browser at [http://localhost:3000](http://localhost:3000)

<!-- START readme-templates/samples-slim-footer.mustache -->
<!-- END readme-templates/samples-slim-footer.mustache -->
