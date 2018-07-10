# Trillian log server

* [Demo log server](https://github.com/projectsbyif/trillian-demo-server) — sets up a virtual machine running a Trillian log server. You can add logs, insert log entries, get log entries, and get proofs about the underlying Merkle tree to allow verifying the integrity of the log.

* [Traffic data publisher example](https://github.com/projectsbyif/trillian-demo-publish) — downloads simulated, hourly counts of road traffic and uses the `trillian` Python library to put it into a Trillian log.

* [Auditor demo](https://github.com/projectsbyif/trillian-demo-audit) — uses the `trillian` Python library to periodically download entries from a log and cryptographically verify them.

* [`trillian` Python library](https://github.com/projectsbyif/trillian-demo-python-api-client) — used by the previous examples, it provides a simple way of inserting and downloading log entries via the log API. Performs some cryptographic validations of the log.
