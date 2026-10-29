# REST API Testing — Postman

A Postman collection of requests written for the **Movie Catalog** educational REST API as part of SoftUni QA training.

## Included requests

1. Register User — `POST`
2. Authenticate User — `POST`
3. Create Movie — `POST`
4. List All Movies — `GET`
5. Edit Movie — `PUT`
6. Delete Movie — `DELETE`

Requests use JSON bodies where applicable and bearer-token authorization for movie operations. The collection includes response assertions for 2xx HTTP status codes, response times below three seconds, and JSON parsing when the response is non-empty. These are **checks configured in Postman**, not proof of a current successful execution.

## Files

- [Postman collection](MovieCatalogAPI.postman_collection.json)
- [Example environment](MovieCatalogAPI.postman_environment.example.json)

## Using the example

Import both JSON files into Postman. Configure `base_url` for an available **authorized testing environment**, and enter your own temporary test values for `test_email`, `test_password`, and `test_username`. Obtain an access token through the authentication request and set `auth_token` before authenticated movie requests. Set `movie_id` to a valid ID returned by the test environment for editing and deletion. Do not send requests to a third-party service without authorization.

The example environment uses `http://localhost:5000` only as a placeholder; it is **not** a claim that the educational application runs on that address. No real passwords or access tokens are included.

**Source context:** API endpoints and their purpose were provided in the coursework specification; the request collection and its organization were authored for the coursework. The original exam documentation is not redistributed here.
