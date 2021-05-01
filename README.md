# agoric-tools
## Monitoring tools for Agoric

Grafana Dashboard JSON
https://github.com/sshamanov/agoric-tools/blob/main/Agoric_Validator_Dashboard.json

Prometheus Rules for AlertManager
https://github.com/sshamanov/agoric-tools/blob/main/agoric-rules.yml

### Monitoring on the Grafana Dashboard
* Consensus and Validator Heights
* Total and Validator Voting Powers
* Total number of Validators and Byzantine/Missing
* Block Size and Average Block time
* Transactions, Total and Uncommited
* Number of connected peers and syncing status
* CPU and Memory statistics from the Node
* Network Rate monitor of the Node
* Status of Alertmanager for being jailed and Height, Power changes

### Prometheus Rules
* Difference in Validator and Consensus Heights
* Validator Voting Power Changes
* Validator was jailed

### Also include HW monitoring from the Node Exporter Metrics

### Screenshot
![image](https://i.imgur.com/uo6BIZF.png)
