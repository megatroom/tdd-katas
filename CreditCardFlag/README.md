# Credit Card Flag

Given the issuer identification number (IIN), write a function that identifies the issuing network according to the credit card number informed.

```js
// Issuer Identification Numbers
const IIN_RANGES = {
  VISA: [4, 56],
  MASTER_CARD: [5],
  DINERS_CLUB: [340,346, 348],
  AMERICAN_EXPRESS: [34, 37]
}

// Call to the function
getCreditCardIssuer(3422341234)

// Result
'AMERICAN_EXPRESS'
```
