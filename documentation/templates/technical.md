# ⚙️ [Technical Name - e.g. CreateOrder]

## 📊 Status

* Status: Draft | Active | Deprecated
* Last Updated: YYYY-MM-DD
* Owner: [Name]

## 📍 Entry Points

* Endpoint: POST /api/orders
* Event / Queue / Job (if applicable)
* Stored Procedure: sp_create_order

## 📦 Contracts

### Request

```json
{
  "userId": "number",
  "items": []
}
```

### Response

```json
{
  "orderId": "number"
}
```

## 🧱 Components Involved

* Controller
* Service
* Repository
* External APIs

## 🔄 Technical Flow

1. Controller receives request
2. Validates input
3. Calls service
4. Persists data

## 🔗 Dependencies

* PaymentService
* InventoryService
* Database (table X)

## ⚠️ Error Handling

* 400 → validation errors
* 500 → internal errors
* Timeout → external services

## 🔐 Security

* Authentication required
* Roles / permissions

## 📊 Considerations

* Transactions
* Performance
* Concurrency

## 🧪 Testing

* Unit tests
* Edge cases

## 📝 Notes

Relevant technical decisions
