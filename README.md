# matsyan-The-Syndicate-Signals----

## 🧠 Data Models (Firestore)

### 🐟 Fish Listing (fish_listings)
```json
{
  "fishName": "Pomfret",
  "weightKg": 2.5,
  "pricePerKg": 300,
  "uploadedBy": "fisherman_uid",
  "freshnessChecklist": {
    "clearEyes": true,
    "redGills": true,
    "firmBody": false
  },
  "status": "pending", // pending | inspected | rejected
  "location": "Chennai Harbour",
  "timestamp": "2025-07-16T09:00:00"
}
