
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/me/mailfolders/inbox/messagerules('AQAAAJ5dZp8=')')
	.version('beta')
	.delete();

```