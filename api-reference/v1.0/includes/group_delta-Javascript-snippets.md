
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/groups/delta')
	.header('Prefer','return=minimal')
	.select('displayName,description,mailNickname')
	.get();

```