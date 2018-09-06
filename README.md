# Trillian Demo

* [trillian-demo-server](https://github.com/projectsbyif/trillian-demo-server) — sets up a virtual machine running a Trillian log server. You can add logs, insert log entries, get log entries, and get proofs about the underlying Merkle tree to allow verifying the integrity of the log.

* [trillian-demo-publish](https://github.com/projectsbyif/trillian-demo-publish) — downloads simulated, hourly counts of road traffic data and uses the Trillian Python library to put it into a Trillian log.

* [trillian-audit-demo](https://github.com/projectsbyif/trillian-demo-audit) — uses the Trillian Python library to periodically download entries from a log and cryptographically verify them.

* [trillian-demo-python-api-client](https://github.com/projectsbyif/trillian-demo-python-api-client) — a library used by the previous examples, providing a simple way of inserting and downloading log entries via the log API. It also performs some cryptographic validations of the log. You can use this library in your own Python applications.
