---
description: "Automatically generated file. DO NOT MODIFY"
---

```javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/identity/b2xUserFlows/{id}/userAttributeAssignments')
	.version('beta')
	.expand('userAttribute')
	.get();

```