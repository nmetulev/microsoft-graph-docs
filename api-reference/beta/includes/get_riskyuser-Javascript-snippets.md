
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/riskyUsers/c2b6c2b9-dddc-acd0-2b39-d519d803dbc3')
	.version('beta')
	.get();

```