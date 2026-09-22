# API Testing with Postman

A collection of hands-on API-testing exercises, Postman collections, data-driven test assets, and generated reports.

## Demonstrated skills

- REST request construction
- Environment and variable usage
- Authentication and headers
- Status, payload, schema, and response-time assertions
- Positive and negative test cases
- Data-driven execution
- Collection reporting

## Repository contents

- Postman collection JSON files
- Data-driven testing exercises
- API test suites
- Generated HTML report

## Run

Import a collection into Postman or execute it with Newman:

```bash
newman run "API Testing.postman_collection.json"
```

Use environment files only when required by a collection, and never commit credentials.
