---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

ItemPhone itemPhone = graphClient.me().profile().phones("{id}")
	.buildRequest()
	.get();

```