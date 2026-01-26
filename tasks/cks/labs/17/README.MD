
|        **17**        | **Enable audit log**                                                                                                                                                                                                                          |
|:-------------------:|:REDACTEDREDACTED|
|     Task weight     | 7%                                                                                                                                                                                                                                            |
|       Cluster       | default                                                                                                                                                                                                                                       |
| Acceptance criteria | - **logs** `/var/logs/kubernetes-api.log`<br/>- **policy** `/etc/kubernetes/policy/log-policy.yaml`<br/>- From `Secret` resources, level `Metadata`, namespace `prod`.<br/>- From `configmaps`, level `RequestResponse`, namespace `billing`. |
---
