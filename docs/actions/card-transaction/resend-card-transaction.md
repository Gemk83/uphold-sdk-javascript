# `.resendCardTransaction()`

Triggers a reminder for a transaction that hasn’t yet been redeemed.

| Argument        | Type   | Required | Description                                              |
|:----------------|:-------|:---------|:---------------------------------------------------------|
| `cardId`        | String | Yes      | Card id                                                  |
| `transactionId` | String | Yes      | Transaction id                                           |
| `options`       | Object | No       | Any options you may want to pass to [`.api()`](/sdk#api) |

This method returns a **Promise**.

Get more details on the [official documentation](https://uphold.com/en/developer/api/documentation/#resend-a-transaction).
