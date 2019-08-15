## Cancel Payment by Idempotency Key Response

Return value from the [CancelPaymentByIdempotencyKey](/doc/payments.md#cancelpaymentbyidempotencykey) endpoint.  On success,
`errors` will be empty.

### Structure

`CancelPaymentByIdempotencyKeyResponse`

### Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `errors` | [`Array<Error Hash>`](/doc/models/error.md) | Optional | Any errors that occurred during the request. |

### Example (as JSON)

```json
{}
```
