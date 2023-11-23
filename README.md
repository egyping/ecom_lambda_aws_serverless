# a serverless ecommerce built on AWS lambda

Lets build a sample ecommerce on AWS with serverless technologies 

TypeScript
serverless framework
AWS Lambda 
AWS SNS 
AWS DynamoDb 
AWS EventBridge 
AWS S3
AWS Cognito

## GET APIs

#### Get all products (open)
```http
  GET /api/products
```

#### Get product (open)
```http
  GET /api/products/${slug}
```

#### Get all Brands (open)
```http
  GET /api/brands
```

#### Get all Tags (open)
```http
  GET /api/tags
```

#### Get Brand (open)
```http
  GET /api/brands/${slug}
```

#### Get tag (open)
```http
  GET /api/products/${slug}
```

#### Get Home page banners (open)
```http
  GET /api/homepage/
```

#### Get cart details (closed)
```http
  GET /api/cart/
```

#### Get orders list (closed)
```http
  GET /api/orders/
```

#### Get order details (closed)
```http
  GET /api/orders/${orderId}
```


## POST and Udate APIs all closed 

#### Post Create product
```http
  GET /api/products/
```

#### Post Create Brand
```http
  GET /api/brands/
```

#### Post Post Create Tag
```http
  GET /api/products/
```

#### Post Create Home page banner
```http
  GET /api/products/
```

#### Post add item to the cart
```http
  GET /api/cart/items
```

#### Delete add item to the cart
```http
  GET /api/cart/items/${itemId}
```

#### Delete cart (closed)
```http
  GET /api/cart/
```

#### Post create order (closed)
```http
  GET /api/orders/
```

#### Update Order status (closed)
```http
  GET /api/orders/${orderId}
```

#### Delete Order (closed)
```http
  GET /api/orders/${orderId}
```


## DynamoDb Tables 

#### Products 

#### Orders

#### Cart

