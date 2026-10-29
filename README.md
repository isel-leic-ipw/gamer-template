# GAMER

The practical component of Web Programming and Architecture course will be developed around **GAMER**
(**G**ames **A**PI, **M**y **E**ntertainment **R**egistry), a web application
for exploring video games and managing personal game collections. The
application obtains its game catalogue information from the [RAWG Video Games
Database API](https://rawg.io/apidocs).

To access RAWG, each student must obtain an API key by registering with the
service. Requests must include the key in the `key` query parameter. The free
API has usage limits; read and comply with the [RAWG API terms and
limits](https://rawg.io/apidocs).

Development will take place incrementally in three parts (Part 1, Part 2 and
Part 3). Each part has its own delivery deadline, which is a non-negotiable
requirement. The application is expected to evolve through refactoring, so use
good programming practices and keep the modules loosely coupled.

For each GAMER functionality, define the corresponding HTTP endpoint. Document
all application endpoints in an
[OpenAPI](https://github.com/OAI/OpenAPI-Specification) file named
`docs/gamer-api-spec.json` (or `.yaml`). Include REST Client-compatible requests
in `docs/gamer-api-requests.http` to validate the API.

Summary of the artifacts to be submitted:
- OpenAPI specification: `docs/gamer-api-spec.[yaml|json]`
- REST Client requests: `docs/gamer-api-requests.http`
- Node.js GAMER application files
