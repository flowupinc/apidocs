![Image of Flowup Inc](https://flowup.com/img/logo-black.png)

Flowup API Docs

You can play with you Contacts using Flowup API Docs

See it in Action : [API Docs](https://flowup.com/apidocs?utm_source=github&utm_medium=readme)

### Create Contact list
This endpoint allows you to Create Contact list using your APIKey.

**HTTP Request**
```
https://beta.flowup.com​/api​/public​/contactManagement​/contactList
```

Query Parameters

1. list_name
2. list_tag
3. country_code
4. campaign_id

```
example: OrderedMap { "list_name": "FlowupAPIDocContacts", "list_tag": List [ OrderedMap { "name": " " } ], "country_code": "+1", "campaign_id": null }
```