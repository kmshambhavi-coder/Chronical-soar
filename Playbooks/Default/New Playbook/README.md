# New Playbook




**Enabled:** True

**Version:** 1

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False


### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|MicrosoftDefenderATP_Execute Live Response Command_1|Use "Execute Live Response Command" action to execute a live response command in Microsoft Defender for Endpoint. Supported Entities: IP Address, Hostname. Note: Action is running as async, please adjust script timeout value in Google SecOps IDE for action, as needed.|MicrosoftDefenderATP|Execute Live Response Command|

Jinja