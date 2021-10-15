# checkfront-app-manifests

## Contributing

Submit a pull request to [manifests.json](./manifests.json) adding your application. We will do our best to get it listed ASAP!

Manifest Format:

```js
"id": {
	"name": "App Name",
	"description": "A brief description of your app.",
	"tokenCallbackUrl": "http://localhost:3000", // We'll redirect the user's browser to a URL of your choice along with API credentials
	"homeUrl": "http://localhost:3000" // Show us where to navigate the user to when they are looking to interact with your app
}
```
