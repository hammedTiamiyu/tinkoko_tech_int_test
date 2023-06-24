## TINKOKO MARKET PLACE BACKEND TECHNICAL INTERVIEW TEST

### Using the aws lambda function,dynamodb and api gateway develop the following Rest api endpints:

#### /create-user (Creating a new user)
#### Payload Structure:
```
    {
    "id": "635fa785a33f428f929919aa", [partion key -pk]
    "activateUser": false,
    "createdAt": "1667213189880",
    "currency": "NGN",
    "lastName": "Lamidi ",
    "email": "lamiditemitope31@email.com" ,
    "firstName": "Temitope ",
    "phone": "7043330737",
    "role": [buyer / seller],
    "userId": "temi247",
    }
```

#### /create-product (Creating a new product)
#### Payload Structure:
```
    {
    "id": "SaiUFv2oJurhMWq92VAesQKF", [pk]
    "category": "627cc555046919d2a6f21662",
    "city": "Abuja",
    "count": 10,
    "country": "Nigeria",
    "createdAt": "1685421412232",
    "description": "Banana Flavour Minimum Order Quantity - 10pcs",
    "images": [
    {
    "public_id": "n4t5ccur0shvzrnwlkoy",
    "url": "https://res.cloudinary.com/tinkokooffice/image/upload/v1685421283/n4t5ccur0shvzrnwlkoy.jpg"
    }
    ],
    "price": "1000",
    "productName": "L&Z Yoghurt ",
    "quantity": 100,
    "subCategory": "hLBxpm6XoCWvhQQdsmRjQPZL",
    "sellerId": "634084c8fd2c16ba75c006e8",
    "weight": "500"
    }
```
#### /update-user/[:user-id] (updating a user record)
#### Payload Structure:
```
    {
    "photo": [
    {
    "public_id": "n4t5ccur0shvzrnwlkoy",
    "url": "https://res.cloudinary.com/tinkokooffice/image/upload/v1685421283/n4t5ccur0shvzrnwlkoy.jpg"
    }
    ],
    "verificationMeans": "National ID"
    "idNumber": "0257248879HGT"
    }
```


