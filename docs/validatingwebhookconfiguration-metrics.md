# ValidatingWebhookConfiguration Metrics

| Metric name| Metric type | Labels/tags | Status |
| ---------- | ----------- | ----------- | ----------- |
| kube_validatingwebhookconfiguration_info | Gauge | `validatingwebhookconfiguration`=&lt;validatingwebhookconfiguration-name&gt; <br> `namespace`=&lt;validatingwebhookconfiguration-namespace&gt; | EXPERIMENTAL |
| kube_validatingwebhookconfiguration_created  | Gauge | `validatingwebhookconfiguration`=&lt;validatingwebhookconfiguration-name&gt; <br> `namespace`=&lt;validatingwebhookconfiguration-namespace&gt; | EXPERIMENTAL |
| kube_validatingwebhookconfiguration_metadata_resource_version | Gauge | `validatingwebhookconfiguration`=&lt;validatingwebhookconfiguration-name&gt; <br> `namespace`=&lt;validatingwebhookconfiguration-namespace&gt; | EXPERIMENTAL |
| kube_validatingwebhookconfiguration_webhook_clientconfig_service | Gauge | `validatingwebhookconfiguration`=&lt;validatingwebhookconfiguration-name&gt; <br> `namespace`=&lt;validatingwebhookconfiguration-namespace&gt; <br> `webhook_name`=&lt;webhook-name&gt; <br> `service_name`=&lt;webhook-service-name&gt; <br> `service_namespace`=&lt;webhook-service-namespace&gt;| EXPERIMENTAL |
