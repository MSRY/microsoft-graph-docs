
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/me/events/{id}/attachments/{id}')
	.delete();

```