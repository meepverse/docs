---
title: Bug Awareness
hide_table_of_contents: false
---

# Known bugs

- When using the file `docker-compose-with-clients-metrics.yml` or `docker-compose-with-clients.yml`, the Diva client will wait until the Ethereum nodes are synced without being able to start. If that happens, the Diva Operator UI might show a `Fetching your node identity...` message that never resolves. 

*If this occurs, restart the Diva client after your Ethereum clients are synced to solve the issue.

You are invited to report any other bugs in the [testnet Github repository](https://github.com/shamirlabs/diva-alpha-net/issues) or [in the #🧨|operator-testnet channel in the Diva Discord](https://discord.com/invite/diva).
