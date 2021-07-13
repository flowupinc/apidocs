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

Parameter | Description
------------ | -------------
list_name | List name which you want to create
list_tag | Tags help in searching for a contact list. Multiple lists can be grouped and identified by using the same tags.
country_code | Helps in overriding your contacts with the selected country code.
campaign_id | Add Id of pre-created campaign for this new contact list.

**Example:**

```
{
  "list_name": "FlowupAPIDocContacts",
  "list_tag": [
    {
      "name": " "
    }
  ],
  "country_code": "+1",
  "campaign_id": null
}
```