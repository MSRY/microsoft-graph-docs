
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const contactFolder = {
  parentFolderId: "parentFolderId-value",
  displayName: "displayName-value"
};

let res = await client.api('/me/contactFolders/{id}')
	.version('beta')
	.update({contactFolder : contactFolder});

```