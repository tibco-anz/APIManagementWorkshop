# Scratchpad

This file contains text snippets you'll need during the workshop to save you typing. Be sure to use your favourite text editor - one that you will know will respect text characters, e.g. not turning valid double-quotes into fancy-looking (but non-legitimate) versions of themselves.

## BillPaymentRequest

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
