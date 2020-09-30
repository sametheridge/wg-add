Features:
- Adds multiple new wireguard clients
- Generates server keys, if not provided

Usage:
`./wg-add <number of clients to add>`

Note:
generates client configs called `client.<ip>`
where `<ip>` is the final octet of the clients IP.
Starts at `.2` because the server is `.1`
