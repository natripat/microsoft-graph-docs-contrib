---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);

$requestBody = new AdminReportSettings();
$requestBody->setDisplayConcealedNames(true);



$result = $graphServiceClient->admin()->reportSettings()->patch($requestBody);


```