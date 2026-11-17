# Assets

Released operations: crud.

Fields and validation rules:

```json
{
  "name": {
    "type": "TEXT",
    "required": true
  },
  "location": {
    "type": "TEXT",
    "required": true
  },
  "status": {
    "type": "TEXT",
    "required": true,
    "choices": [
      "operating",
      "maintenance",
      "retired"
    ]
  }
}
```

API: `/api/assets`. CSV import: POST `/api/assets/import` with a JSON `csv` field when released. Summary: GET `/api/assets/report` when released. Search: GET `/api/assets?q=term&limit=50&offset=0` when released. PUT `/api/assets/ID` accepts `record` and the last observed `version`; stale updates are rejected.
