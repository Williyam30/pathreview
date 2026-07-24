# Solution Plan

**Issue**

API docs don't include example curl commands

https://github.com/ascherj/pathreview/issues/117

## Understand

The API documentation lists all available endpoints but does not provide 
example curl commands. Developers must manually determine request 
methods, headers, and JSON payloads before testing the API. Adding copy 
and paste examples will make onboarding much easier.


## Map

Files involved:

- docs/API.md

Reference files:

- api/routes/
- README.md
- OpenAPI documentation at localhost:8000/docs

## Plan

1. Review every endpoint documented in API.md.
2. Verify request methods and required JSON bodies.
3. Write example curl commands for each endpoint.
4. Keep formatting consistent with the existing documentation.
5. Verify examples against the local development server if possible.


## Inputs & Outputs

Input:

Current API documentation.

Output:

Updated documentation with complete curl examples for every endpoint.


## Risks & Unknowns

- Some endpoints require authentication tokens.
- Need to verify exact JSON payloads.
- Endpoint paths may differ from assumptions.

## Edge Cases

- Authenticated endpoints should clearly indicate Authorization headers.
- Examples should use localhost.
- JSON formatting should be copy-paste ready.


