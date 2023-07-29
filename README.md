# BookBridge-API-Backend

### API Endpoints:

![Screenshot (280)](https://github.com/PritamSarbajna/BookBridge-API-Backend/assets/90236635/bf03d1e9-482f-488f-9f63-df8b7a2e64fc)

## API Usage:

#### URL : /
#### Method : GET

-----------------------------------------------------------------------------------------------------

#### URL : /register/
#### Method : POST
#### Request Body:
```
{
  "name": "string",
  "email": "string",
  "password": "string"
}
```

-----------------------------------------------------------------------------------------------------

#### URL : /login
#### Method : POST
#### Request Body:
```
{
  "email": "string",
  "password": "string"
}
```

-----------------------------------------------------------------------------------------------------

#### URL : /login
#### Method : POST
#### Request Body:
```
{
  "email": "string",
  "password": "string"
}
```

-----------------------------------------------------------------------------------------------------

#### URL : /addbooks
#### Method : POST
#### Request Body:
```
file_upload [ string($binary) ]
email [ string ]
book [ string ]
author [ string ]
country [ string ]
state [ string ]
tags [ string ]
description [ string ]
```

-----------------------------------------------------------------------------------------------------

#### URL : /userbooks/{email}
#### Method : GET
#### Request Body:
```
email [ string ]
```

-------------------------------------------------------------------------------------------------------

#### URL : /allbooks
#### Method : GET

-----------------------------------------------------------------------------------------------------

#### URL : /allbooks/{id}
#### Method : GET

```
id [ integer ]
```

-----------------------------------------------------------------------------------------------------

#### URL : /send_message
#### Method : POST
#### Request Body:
```
{
  "sender_email": "string",
  "receiver_email": "string",
  "message": "string"
}
```

-----------------------------------------------------------------------------------------------------

#### URL : /chat_history/{sender_email}/{receiver_email}
#### Method : GET

```
sender_email [ string ]
receiver_email [ string ]
```

-----------------------------------------------------------------------------------------------------

#### URL : /chat_emails/{email}
#### Method : GET

```
email [ string ]
```
