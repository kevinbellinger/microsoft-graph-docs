---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

await graphClient.Me.Authentication.PhoneMethods["3179e48a-750b-4051-897c-87b9720928f7"]
	.EnableSmsSignIn()
	.Request()
	.PostAsync();

```