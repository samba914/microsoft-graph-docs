---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var user = await graphClient.Education.Me.User
	.Request()
	.GetAsync();

```