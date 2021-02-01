# Scratchpad

This file contains text snippets you'll need during the workshop to save you typing. Be sure to use your favourite text editor - one that you will know will respect text characters, e.g. not turning valid double-quotes into fancy-looking (but non-legitimate) versions of themselves.


## API Modelling

### Naming

API: 
```
BillPayment
```

Resource:
```
/billPayment
```

API Key:
```
api_key
```

### BillPaymentRequest

```
{
    "billId": "12345",
    "totalAmount": {
        "unit": "AUD",
        "value": 24.95
    },
    "paymentMethod": {
        "id": "15492654",
        "referredType": "Voucher"
    }
}
```

## BillPaymentResponse

```
{
    "id": "323553",
    "paymentDate": "2020-01-08T12:06:38.230Z",
    "billId": "12345",
    "totalAmount": {
        "unit": "AUD",
        "value": 24.95
    },
    "paymentMethod": {
        "id": "15492654",
        "referredType": "Voucher"
    }
}
```

## Orchestrating Services

### BillPayment Test Body

```
{
    "billId": "325366",
    "totalAmount": {
        "unit": "AUD",
        "value": 29.95
    },
    "paymentMethod": {
        "id": "73432381",
        "referredType": "Voucher"
    }
}
```

## Exposing an API

### TIBCO Cloud Mashery URL
https://account.cloud.tibco.com/launchtenant/MASHERY
