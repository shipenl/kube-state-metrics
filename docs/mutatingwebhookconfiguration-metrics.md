# MutatingWebhookConfiguration Metrics

| Metric name| Metric type | Labels/tags | Status |
| ---------- | ----------- | ----------- | ----------- |
| kube_mutatingwebhookconfiguration_info | Gauge | `mutatingwebhookconfiguration`=&lt;mutatingwebhookconfiguration-name&gt; <br> `namespace`=&lt;mutatingwebhookconfiguration-namespace&gt; | EXPERIMENTAL |
| kube_mutatingwebhookconfiguration_created  | Gauge | `mutatingwebhookconfiguration`=&lt;mutatingwebhookconfiguration-name&gt; <br> `namespace`=&lt;mutatingwebhookconfiguration-namespace&gt; | EXPERIMENTAL |
| kube_mutatingwebhookconfiguration_metadata_resource_version | Gauge | `mutatingwebhookconfiguration`=&lt;mutatingwebhookconfiguration-name&gt; <br> `namespace`=&lt;mutatingwebhookconfiguration-namespace&gt; | EXPERIMENTAL |
| kube_mutatingwebhookconfiguration_webhook_clientconfig_service | Gauge | `mutatingwebhookconfiguration`=&lt;mutatingwebhookconfiguration-name&gt; <br> `namespace`=&lt;mutatingwebhookconfiguration-namespace&gt; <br> `webhook_name`=&lt;webhook-name&gt; <br> `service_name`=&lt;webhook-service-name&gt; <br> `service_namespace`=&lt;webhook-service-namespace&gt;| EXPERIMENTAL |
