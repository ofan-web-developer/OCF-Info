
# Buyer
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/account

// body parameter
init = 'buyer-login'
pack = {fieldForm:{username:XXXX, password:XXXX}}
```
# Seller
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/account

// body parameter
init = 'seller-follow'
pack = {fieldForm:{seller_id:XXXX, following:[true/false]}}
```
# Product
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/sensus

// body parameter
init = 'product-detail'
pack = {fieldForm:{id:XXXX}}
```
# Order
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/transaction

// body parameter
init = 'order-list'
pack = {fieldForm:{id:XXXX}}
```
# Payment
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/transaction

// body parameter
init = 'payment-list'
pack = {fieldForm:{type:XXXX}}
```
# Shipping
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/transaction

// body parameter
init = 'shipping-calculate'
pack = {fieldForm:{from:XXX, to:XXX, weight:XXX, vendor:XXX, quantity:XXX}}
```
# Mailling
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/cabinet

// body parameter
init = 'mail-order'
pack = {fieldForm:{from:XXX, message:XXX}}
```
# SMS Notification
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/cabinet

// body parameter
init = 'sms-order'
pack = {fieldForm:{from:XXX, message:XXX}}
```
# Push Notification
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/cabinet

// body parameter
init = 'push-order'
pack = {fieldForm:{from:XXX, message:XXX}}
```
# Config
```typescript
// url endpoint
https://api.bumdesapp.com/v2/m3/config

// body parameter
init = 'config-list'
pack = {fieldForm:{type:XXX}}
```