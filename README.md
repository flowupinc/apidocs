![Image of Flowup Inc](https://flowup.com/img/logo-black.png)

Flowup API Docs

You can play with you Contacts using Flowup API Docs

See it in Action : [API Docs](https://flowup.com/apidocs?utm_source=github&utm_medium=readme)

## Create Contact list
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

## Create contact
This endpoint allows you to Create Contact using your APIKey.

**HTTP Request**
```
https://beta.flowup.com​/​api​/public​/contactManagement​/contact
```

Query Parameters

Parameter | Description
------------ | -------------
contact_list_id | Id of Contact List to Store this contact in.
title | Contact title ex. Mr. or Mrs.
first_name | Name of you contact.
middle_name | Middle name of your contact.
last_name | Last name of your contact.
email | Email id of your contact
gender | Gender of your contact. 
state | State of your contact.
city | City of your contact.
postal_code | Postal code of your contact.
address | Address of your contact.
phone_code | Phone code of your contact.
phone_number | Phone Number of your contact.
is_dnc_check | Do you want check that contact number is in DNC list or not?
is_duplicate_check | Do you want check that contact number is duplicate or not?

**Example:**
```
{
  "contact_list_id": 123,
  "title": "Mr",
  "first_name": "David",
  "middle_name": "S",
  "last_name": "Solomon",
  "email": "david@comapany.com",
  "gender": "Male",
  "state": "Texas",
  "city": "Dallas",
  "postal_code": "75001",
  "address": "AMLI 7th Street Station 2601 West 7th St.",
  "phone_code": "+1",
  "phone_number": "8178771977",
  "is_dnc_check": false,
  "is_duplicate_check": false
}
```