REST
====

Example questions for candidates who have a good understanding of REST,
and of designing high quality RESTful APIs.

---

Q: How do you approach the problem of designing a good API?

A: Research best practices in blogs and books.
Extra credit if the candidate can name his sources.

---

Q: What are the different HTTP request methods, and how to use them?

A: GET, POST, PUT, DELETE, HEAD, OPTIONS, PATCH

Extra credit for knowing any of the last 3.

---

Q: Name some mandatory and some optional HTTP header fields

A: Mandatory: Content-Type. Optional examples: Content-length, Status,
Location, Set-Cookie, User-Agent, Cache-Control

---

Q: What are the different HTTP error message types, and how to use them?

A: 1xx, 2xx, 3xx, 4xx, 5xx

- 2xx: success
- 3xx: redirected
- 4xx: client error
- 5xx: server error

---

Q: Consider this URI scheme:

- `/clients` returns the list of complete client objects
- `/clients/:id` returns the complete client object with the specified ID

How would you add support for a new feature to get only selected fields
of clients instead of complete objects?

A: Use query parameters to specify a filter,
for example: `/clients/?fields=(name,email)`

Extra credit for knowing the recommended listing format `(..., ...)`

---

Q: How would you organize your project exposing a RESTful API?

For example, if you have `example.org` as domain name,
what would you choose for the URI of the following elements:

- REST API
- Developer portal
- Official project homepage

A: The common approach:

- REST API: `api.example.org`
- Developer portal: `developer.example.org`
- Official project homepage: `example.org`

---

Other simple questions:

- Which HTTP request method would you use to check if a resource exists? -> HEAD
- What is the status code of success? -> 200
- What is the status code of a server error? -> 500
- How to prevent web crawlers from exploring some parts of the site? -> robots.txt
- What are some common mistakes when using the JSON format? -> not quoting
  attribute names, using single quotes instead of double, not wrapping in `{}`
