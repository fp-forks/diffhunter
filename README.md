# DiffHunter

An app with focus on normalization, equalization and database scheme migration for distributed arquitecture, micro services or multiple schemes.

# Requirements
- [flask](https://github.com/pallets/flask)
- [sqlalchemy-dff](https://github.com/gianchub/sqlalchemy-diff)

Python >= 3.8.5

---

TODO

- Endpoint for calculating the inconsistency value
Request:
```http
GET /diffhunter/inconsistency
```

Response:
```json
{
	"inconsistency_value": 20.155
}
```
- Endpoint for returning the comparison between two databases
```json
{
	"origin": {"name": "mydatabase"},
	"target": {"name": ""}
}
```
- Endpoint for returning the comparison between mutiple databases
```json
{
	"origin": {},
	"targets": []
}
```
- Differences in Tables (Endpoint)
- Differences in Primary Keys for a common table (Endpoint)
- Differences in Foreign Keys for a common table (Endpoint)
- Differences in Indexes for a common table (Endpoint)
- Differences in Columns for a common table (Endpoint)
- Frontend
