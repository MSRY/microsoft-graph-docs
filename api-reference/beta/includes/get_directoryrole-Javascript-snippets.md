
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/directoryRoles/{id}')
	.version('beta')
	.get();

```