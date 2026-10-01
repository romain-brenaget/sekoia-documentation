# v2_other_tabs

Intro paragraph.

{% tabs %}
{% tab title="gke_log_id_event.json" %}

{% code overflow="wrap" expandable="true" %}
```json
{
    "message": "{\n  \"insertId\": \"17ahw8eg29q74y6\",\n  \"jsonPayload\": {\n    \"reportingComponent\": \"\",\n    \"reason\": \"Pulling\",\n    \"eventTime\": null,\n    \"reportingInstance\": \"\",\n    \"kind\": \"Event\",\n    \"message\": \"Pulling image \\\"gke.gcr.io/prometheus-to-sd:v0.11.3-gke.0\\\"\",\n    \"apiVersion\": \"v1\",\n    \"type\": \"Normal\",\n    \"source\": {\n      \"host\": \"gke-cluster-1-default-pool-476246ab-wnl7\",\n      \"component\": \"kubelet\"\n    },\n    \"metadata\": {\n      \"resourceVersion\": \"954\",\n      \"creationTimestamp\": \"2022-06-01T14:05:30Z\",\n      \"namespace\": \"kube-system\",\n      \"managedFields\": [\n        {\n          \"manager\": \"kubelet\",\n          \"apiVersion\": \"v1\",\n          \"fieldsV1\": {\n            \"f:message\": {},\n            \"f:involvedObject\": {},\n            \"f:lastTimestamp\": {},\n            \"f:source\": {\n              \"f:host\": {},\n              \"f:component\": {}\n            },\n            \"f:type\": {},\n            \"f:reason\": {},\n            \"f:count\": {},\n            \"f:firstTimestamp\": {}\n          },\n          \"operation\": \"Update\",\n          \"fieldsType\": \"FieldsV1\",\n          \"time\": \"2022-06-01T14:05:30Z\"\n        }\n      ],\n      \"uid\": \"658b3d26-ed26-4d32-a5b4-3bb87bdefa99\",\n      \"name\": \"kube-dns-56494768b7-544n6.16f48435f72a4bd9\"\n    },\n    \"involvedObject\": {\n      \"resourceVersion\": \"6551\",\n      \"namespace\": \"kube-system\",\n      \"fieldPath\": \"spec.containers{prometheus-to-sd}\",\n      \"apiVersion\": \"v1\",\n      \"name\": \"kube-dns-56494768b7-544n6\",\n      \"uid\": \"52017f74-5157-4788-a62e-b83c4eac4acf\",\n      \"kind\": \"Pod\"\n    }\n  },\n  \"resource\": {\n    \"type\": \"k8s_pod\",\n    \"labels\": {\n      \"location\": \"europe-west1-c\",\n      \"namespace_name\": \"kube-system\",\n      \"cluster_name\": \"cluster-1\",\n      \"pod_name\": \"kube-dns-56494768b7-544n6\",\n      \"project_id\": \"hazel-aria-348413\"\n    }\n  },\n  \"timestamp\": \"2022-06-01T14:05:30Z\",\n  \"severity\": \"INFO\",\n  \"logName\": \"projects/hazel-aria-348413/logs/events\",\n  \"receiveTimestamp\": \"2022-06-01T14:05:39.683992581Z\"\n}",
    "event": {
        "action": "Pulling",
        "category": [
            "process"
        ],
        "reason": "Pulling image \"gke.gcr.io/prometheus-to-sd:v0.11.3-gke.0\"",
        "type": [
            "change"
        ]
    },
    "@timestamp": "2022-06-01T14:05:30Z",
    "cloud": {
        "project": {
            "id": "hazel-aria-348413"
        }
    },
    "google_kubernetes_engine": {
        "insertId": "17ahw8eg29q74y6",
        "jsonPayload": {
            "apiVersion": "v1",
            "involvedObject": {
                "fieldPath": "spec.containers{prometheus-to-sd}",
                "kind": "Pod",
                "name": "kube-dns-56494768b7-544n6",
                "resourceVersion": "6551",
                "uid": "52017f74-5157-4788-a62e-b83c4eac4acf"
            },
            "kind": "Event",
            "metadata": {
                "creationTimestamp": "2022-06-01T14:05:30Z",
                "managedFields": [
                    {
                        "apiVersion": "v1",
                        "fieldsType": "FieldsV1",
                        "fieldsV1": {
                            "f:count": {},
                            "f:firstTimestamp": {},
                            "f:involvedObject": {},
                            "f:lastTimestamp": {},
                            "f:message": {},
                            "f:reason": {},
                            "f:source": {
                                "f:component": {},
                                "f:host": {}
                            },
                            "f:type": {}
                        },
                        "manager": "kubelet",
                        "operation": "Update",
                        "time": "2022-06-01T14:05:30Z"
                    }
                ],
                "resourceVersion": "954",
                "uid": "658b3d26-ed26-4d32-a5b4-3bb87bdefa99"
            },
            "source": {
                "component": "kubelet"
            },
            "type": "Normal"
        },
        "logName": "projects/hazel-aria-348413/logs/events",
        "receiveTimestamp": "2022-06-01T14:05:39.683992581Z",
        "severity": "INFO"
    },
    "host": {
        "name": "gke-cluster-1-default-pool-476246ab-wnl7"
    },
    "orchestrator": {
        "api_version": "v1",
        "cluster": {
            "name": "cluster-1"
        },
        "namespace": "kube-system",
        "resource": {
            "name": "kube-dns-56494768b7-544n6",
            "type": "k8s_pod"
        },
        "type": "kubernetes"
    },
    "server": {
        "geo": {
            "name": "europe-west1-c"
        }
    }
}
```
{% endcode %}
{% endtab %}
{% tab title="gke_log_id_event2.json" %}

{% code overflow="wrap" expandable="true" %}
```json
{
    "message": "{\n  \"insertId\": \"17ahw8eg29q74yc\",\n  \"jsonPayload\": {\n    \"eventTime\": null,\n    \"reportingInstance\": \"\",\n    \"type\": \"Warning\",\n    \"reportingComponent\": \"\",\n    \"metadata\": {\n      \"resourceVersion\": \"960\",\n      \"name\": \"kube-dns.16f484369d214dae\",\n      \"namespace\": \"kube-system\",\n      \"uid\": \"828b8cd3-1eec-4093-95fb-907ebeab0efa\",\n      \"creationTimestamp\": \"2022-06-01T14:05:33Z\",\n      \"managedFields\": [\n        {\n          \"apiVersion\": \"v1\",\n          \"operation\": \"Update\",\n          \"fieldsV1\": {\n            \"f:firstTimestamp\": {},\n            \"f:involvedObject\": {},\n            \"f:reason\": {},\n            \"f:count\": {},\n            \"f:lastTimestamp\": {},\n            \"f:type\": {},\n            \"f:message\": {},\n            \"f:source\": {\n              \"f:component\": {}\n            }\n          },\n          \"manager\": \"kube-controller-manager\",\n          \"time\": \"2022-06-01T14:05:33Z\",\n          \"fieldsType\": \"FieldsV1\"\n        }\n      ]\n    },\n    \"apiVersion\": \"v1\",\n    \"kind\": \"Event\",\n    \"message\": \"Failed to update endpoint kube-system/kube-dns: Operation cannot be fulfilled on endpoints \\\"kube-dns\\\": the object has been modified; please apply your changes to the latest version and try again\",\n    \"source\": {\n      \"component\": \"endpoint-controller\"\n    },\n    \"involvedObject\": {\n      \"apiVersion\": \"v1\",\n      \"uid\": \"75cc3b54-2a5f-42fa-8dd9-1669695113cd\",\n      \"kind\": \"Endpoints\",\n      \"namespace\": \"kube-system\",\n      \"resourceVersion\": \"7416\",\n      \"name\": \"kube-dns\"\n    },\n    \"reason\": \"FailedToUpdateEndpoint\"\n  },\n  \"resource\": {\n    \"type\": \"k8s_cluster\",\n    \"labels\": {\n      \"cluster_name\": \"cluster-1\",\n      \"location\": \"europe-west1-c\",\n      \"project_id\": \"hazel-aria-348413\"\n    }\n  },\n  \"timestamp\": \"2022-06-01T14:05:33Z\",\n  \"severity\": \"WARNING\",\n  \"logName\": \"projects/hazel-aria-348413/logs/events\",\n  \"receiveTimestamp\": \"2022-06-01T14:05:39.683992581Z\"\n}",
    "event": {
        "action": "FailedToUpdateEndpoint",
        "category": [
            "process"
        ],
        "reason": "Failed to update endpoint kube-system/kube-dns: Operation cannot be fulfilled on endpoints \"kube-dns\": the object has been modified; please apply your changes to the latest version and try again",
        "type": [
            "change"
        ]
    },
    "@timestamp": "2022-06-01T14:05:33Z",
    "cloud": {
        "project": {
            "id": "hazel-aria-348413"
        }
    },
    "google_kubernetes_engine": {
        "insertId": "17ahw8eg29q74yc",
        "jsonPayload": {
            "apiVersion": "v1",
            "involvedObject": {
                "kind": "Endpoints",
                "name": "kube-dns",
                "resourceVersion": "7416",
                "uid": "75cc3b54-2a5f-42fa-8dd9-1669695113cd"
            },
            "kind": "Event",
            "metadata": {
                "creationTimestamp": "2022-06-01T14:05:33Z",
                "managedFields": [
                    {
                        "apiVersion": "v1",
                        "fieldsType": "FieldsV1",
                        "fieldsV1": {
                            "f:count": {},
                            "f:firstTimestamp": {},
                            "f:involvedObject": {},
                            "f:lastTimestamp": {},
                            "f:message": {},
                            "f:reason": {},
                            "f:source": {
                                "f:component": {}
                            },
                            "f:type": {}
                        },
                        "manager": "kube-controller-manager",
                        "operation": "Update",
                        "time": "2022-06-01T14:05:33Z"
                    }
                ],
                "resourceVersion": "960",
                "uid": "828b8cd3-1eec-4093-95fb-907ebeab0efa"
            },
            "source": {
                "component": "endpoint-controller"
            },
            "type": "Warning"
        },
        "logName": "projects/hazel-aria-348413/logs/events",
        "receiveTimestamp": "2022-06-01T14:05:39.683992581Z",
        "severity": "WARNING"
    },
    "host": {
        "name": "kube-dns.16f484369d214dae"
    },
    "orchestrator": {
        "api_version": "v1",
        "cluster": {
            "name": "cluster-1"
        },
        "namespace": "kube-system",
        "resource": {
            "type": "k8s_cluster"
        },
        "type": "kubernetes"
    },
    "server": {
        "geo": {
            "name": "europe-west1-c"
        }
    }
}
```
{% endcode %}
{% endtab %}
{% tab title="gke_log_id_event3.json" %}

{% code overflow="wrap" expandable="true" %}
```json
{
    "message": "{\n  \"insertId\": \"17ahw8eg29q74yb\",\n  \"jsonPayload\": {\n    \"involvedObject\": {\n      \"namespace\": \"kube-system\",\n      \"uid\": \"52017f74-5157-4788-a62e-b83c4eac4acf\",\n      \"kind\": \"Pod\",\n      \"resourceVersion\": \"6551\",\n      \"fieldPath\": \"spec.containers{prometheus-to-sd}\",\n      \"apiVersion\": \"v1\",\n      \"name\": \"kube-dns-56494768b7-544n6\"\n    },\n    \"kind\": \"Event\",\n    \"apiVersion\": \"v1\",\n    \"eventTime\": null,\n    \"reportingInstance\": \"\",\n    \"metadata\": {\n      \"managedFields\": [\n        {\n          \"time\": \"2022-06-01T14:05:32Z\",\n          \"manager\": \"kubelet\",\n          \"fieldsType\": \"FieldsV1\",\n          \"operation\": \"Update\",\n          \"apiVersion\": \"v1\",\n          \"fieldsV1\": {\n            \"f:count\": {},\n            \"f:type\": {},\n            \"f:involvedObject\": {},\n            \"f:source\": {\n              \"f:component\": {},\n              \"f:host\": {}\n            },\n            \"f:reason\": {},\n            \"f:firstTimestamp\": {},\n            \"f:message\": {},\n            \"f:lastTimestamp\": {}\n          }\n        }\n      ],\n      \"namespace\": \"kube-system\",\n      \"creationTimestamp\": \"2022-06-01T14:05:32Z\",\n      \"name\": \"kube-dns-56494768b7-544n6.16f48436899e3f4a\",\n      \"resourceVersion\": \"959\",\n      \"uid\": \"2836bb34-8703-4475-a7d8-5cf0ec2232f8\"\n    },\n    \"message\": \"Created container prometheus-to-sd\",\n    \"reason\": \"Created\",\n    \"type\": \"Normal\",\n    \"source\": {\n      \"host\": \"gke-cluster-1-default-pool-476246ab-wnl7\",\n      \"component\": \"kubelet\"\n    },\n    \"reportingComponent\": \"\"\n  },\n  \"resource\": {\n    \"type\": \"k8s_pod\",\n    \"labels\": {\n      \"project_id\": \"hazel-aria-348413\",\n      \"namespace_name\": \"kube-system\",\n      \"cluster_name\": \"cluster-1\",\n      \"pod_name\": \"kube-dns-56494768b7-544n6\",\n      \"location\": \"europe-west1-c\"\n    }\n  },\n  \"timestamp\": \"2022-06-01T14:05:32Z\",\n  \"severity\": \"INFO\",\n  \"logName\": \"projects/hazel-aria-348413/logs/events\",\n  \"receiveTimestamp\": \"2022-06-01T14:05:39.683992581Z\"\n}",
    "event": {
        "action": "Created",
        "category": [
            "process"
        ],
        "reason": "Created container prometheus-to-sd",
        "type": [
            "change"
        ]
    },
    "@timestamp": "2022-06-01T14:05:32Z",
    "cloud": {
        "project": {
            "id": "hazel-aria-348413"
        }
    },
    "google_kubernetes_engine": {
        "insertId": "17ahw8eg29q74yb",
        "jsonPayload": {
            "apiVersion": "v1",
            "involvedObject": {
                "fieldPath": "spec.containers{prometheus-to-sd}",
                "kind": "Pod",
                "name": "kube-dns-56494768b7-544n6",
                "resourceVersion": "6551",
                "uid": "52017f74-5157-4788-a62e-b83c4eac4acf"
            },
            "kind": "Event",
            "metadata": {
                "creationTimestamp": "2022-06-01T14:05:32Z",
                "managedFields": [
                    {
                        "apiVersion": "v1",
                        "fieldsType": "FieldsV1",
                        "fieldsV1": {
                            "f:count": {},
                            "f:firstTimestamp": {},
                            "f:involvedObject": {},
                            "f:lastTimestamp": {},
                            "f:message": {},
                            "f:reason": {},
                            "f:source": {
                                "f:component": {},
                                "f:host": {}
                            },
                            "f:type": {}
                        },
                        "manager": "kubelet",
                        "operation": "Update",
                        "time": "2022-06-01T14:05:32Z"
                    }
                ],
                "resourceVersion": "959",
                "uid": "2836bb34-8703-4475-a7d8-5cf0ec2232f8"
            },
            "source": {
                "component": "kubelet"
            },
            "type": "Normal"
        },
        "logName": "projects/hazel-aria-348413/logs/events",
        "receiveTimestamp": "2022-06-01T14:05:39.683992581Z",
        "severity": "INFO"
    },
    "host": {
        "name": "gke-cluster-1-default-pool-476246ab-wnl7"
    },
    "orchestrator": {
        "api_version": "v1",
        "cluster": {
            "name": "cluster-1"
        },
        "namespace": "kube-system",
        "resource": {
            "name": "kube-dns-56494768b7-544n6",
            "type": "k8s_pod"
        },
        "type": "kubernetes"
    },
    "server": {
        "geo": {
            "name": "europe-west1-c"
        }
    }
}
```
{% endcode %}
{% endtab %}
{% tab title="k8s_node.json" %}

{% code overflow="wrap" expandable="true" %}
```json
{
    "message": "{\"insertId\":\"32ez47f5wz17i\",\"jsonPayload\":{\"apiVersion\":\"v1\",\"eventTime\":null,\"involvedObject\":{\"kind\":\"Node\",\"name\":\"gke-cluster-1-default-pool-eb66079e-k3zf\",\"uid\":\"gke-cluster-1-default-pool-eb66079e-k3zf\"},\"kind\":\"Event\",\"message\":\"{\\\"unmanaged\\\": {\\\"net.netfilter.nf_conntrack_buckets\\\": \\\"32768\\\"}}\",\"metadata\":{\"creationTimestamp\":\"2022-06-15T01:55:51Z\",\"managedFields\":[{\"apiVersion\":\"v1\",\"fieldsType\":\"FieldsV1\",\"fieldsV1\":{\"f:count\":{},\"f:firstTimestamp\":{},\"f:involvedObject\":{},\"f:lastTimestamp\":{},\"f:message\":{},\"f:reason\":{},\"f:source\":{\"f:component\":{},\"f:host\":{}},\"f:type\":{}},\"manager\":\"node-problem-detector\",\"operation\":\"Update\",\"time\":\"2022-06-15T01:55:51Z\"}],\"name\":\"gke-cluster-1-default-pool-eb66079e-k3zf.16f8813a8514b8c0\",\"namespace\":\"default\",\"resourceVersion\":\"894\",\"uid\":\"7e26b736-331a-4896-961f-96688918ba7e\"},\"reason\":\"NodeSysctlChange\",\"reportingComponent\":\"\",\"reportingInstance\":\"\",\"source\":{\"component\":\"sysctl-monitor\",\"host\":\"gke-cluster-1-default-pool-eb66079e-k3zf\"},\"type\":\"Warning\"},\"logName\":\"projects/hazel-aria-348413/logs/events\",\"receiveTimestamp\":\"2022-06-15T01:55:52.012275121Z\",\"resource\":{\"labels\":{\"cluster_name\":\"cluster-1\",\"location\":\"europe-central2-a\",\"node_name\":\"gke-cluster-1-default-pool-eb66079e-k3zf\",\"project_id\":\"hazel-aria-348413\"},\"type\":\"k8s_node\"},\"severity\":\"WARNING\",\"timestamp\":\"2022-06-15T01:55:51Z\"}",
    "event": {
        "action": "NodeSysctlChange",
        "category": [
            "process"
        ],
        "reason": "{\"unmanaged\":{\"net.netfilter.nf_conntrack_buckets\":\"32768\"}}",
        "type": [
            "change"
        ]
    },
    "@timestamp": "2022-06-15T01:55:51Z",
    "cloud": {
        "project": {
            "id": "hazel-aria-348413"
        }
    },
    "google_kubernetes_engine": {
        "insertId": "32ez47f5wz17i",
        "jsonPayload": {
            "apiVersion": "v1",
            "involvedObject": {
                "kind": "Node",
                "name": "gke-cluster-1-default-pool-eb66079e-k3zf",
                "uid": "gke-cluster-1-default-pool-eb66079e-k3zf"
            },
            "kind": "Event",
            "metadata": {
                "creationTimestamp": "2022-06-15T01:55:51Z",
                "managedFields": [
                    {
                        "apiVersion": "v1",
                        "fieldsType": "FieldsV1",
                        "fieldsV1": {
                            "f:count": {},
                            "f:firstTimestamp": {},
                            "f:involvedObject": {},
                            "f:lastTimestamp": {},
                            "f:message": {},
                            "f:reason": {},
                            "f:source": {
                                "f:component": {},
                                "f:host": {}
                            },
                            "f:type": {}
                        },
                        "manager": "node-problem-detector",
                        "operation": "Update",
                        "time": "2022-06-15T01:55:51Z"
                    }
                ],
                "resourceVersion": "894",
                "uid": "7e26b736-331a-4896-961f-96688918ba7e"
            },
            "source": {
                "component": "sysctl-monitor"
            },
            "type": "Warning"
        },
        "logName": "projects/hazel-aria-348413/logs/events",
        "receiveTimestamp": "2022-06-15T01:55:52.012275121Z",
        "severity": "WARNING"
    },
    "host": {
        "name": "gke-cluster-1-default-pool-eb66079e-k3zf"
    },
    "orchestrator": {
        "cluster": {
            "name": "cluster-1"
        },
        "namespace": "default",
        "resource": {
            "type": "k8s_node"
        },
        "type": "kubernetes"
    },
    "server": {
        "geo": {
            "name": "europe-central2-a"
        }
    }
}
```
{% endcode %}
{% endtab %}
{% tab title="k8s_textPayload.json" %}

{% code overflow="wrap" expandable="true" %}
```json
{
    "message": "{\"insertId\":\"1wtrhknf2gg14w\",\"logName\":\"projects/hazel-aria-348413/logs/events\",\"receiveTimestamp\":\"2022-06-16T09:42:59.259491841Z\",\"resource\":{\"labels\":{\"cluster_name\":\"cluster-1\",\"location\":\"europe-central2-a\",\"project_id\":\"hazel-aria-348413\"},\"type\":\"k8s_cluster\"},\"severity\":\"WARNING\",\"textPayload\":\"Event exporter started watching. Some events may have been lost up to this point.\",\"timestamp\":\"2022-06-16T09:42:39.200653463Z\"}",
    "event": {
        "category": [
            "process"
        ],
        "reason": "Event exporter started watching. Some events may have been lost up to this point.",
        "type": [
            "change"
        ]
    },
    "@timestamp": "2022-06-16T09:42:39.200653Z",
    "cloud": {
        "project": {
            "id": "hazel-aria-348413"
        }
    },
    "google_kubernetes_engine": {
        "insertId": "1wtrhknf2gg14w",
        "logName": "projects/hazel-aria-348413/logs/events",
        "receiveTimestamp": "2022-06-16T09:42:59.259491841Z",
        "severity": "WARNING"
    },
    "orchestrator": {
        "cluster": {
            "name": "cluster-1"
        },
        "type": "kubernetes"
    },
    "server": {
        "geo": {
            "name": "europe-central2-a"
        }
    }
}
```
{% endcode %}
{% endtab %}
{% tab title="stdout_event_1.json" %}

{% code overflow="wrap" expandable="true" %}
```json
{
    "message": "{\"insertId\":\"1111111111111111\",\"jsonPayload\":{\"additional\":{\"pixyl-analysis-id\":\"analysis-1111111-1\"},\"context\":\"default\",\"logger\":\"ai.gleamer.inference.core.wlm.ReaderThread.pixyl_loggers.loggers.GleamerJSONFormatter\",\"message\":\"{1: 1}\",\"thread\":\"W-8081-Thread-stdout\"},\"labels\":{\"compute.googleapis.com/resource_name\":\"gtest-resource\",\"k8s-pod/app_kubernetes_io/managed-by\":\"Manager\",\"k8s-pod/app_kubernetes_io/name\":\"test-integration-eu-3-3-0\",\"k8s-pod/app_kubernetes_io/version\":\"3.3.0\",\"k8s-pod/gleamer_ai/connector-name\":\"test-integration-eu\",\"k8s-pod/gleamer_ai/connector-version\":\"3.3.0\",\"k8s-pod/manager_sh/chart\":\"app-0.1.0\",\"k8s-pod/pod-template-hash\":\"1111111111\",\"logging.gke.io/top_level_controller_name\":\"test-integration-eu-3-3-0\",\"logging.gke.io/top_level_controller_type\":\"Deployment\"},\"logName\":\"projects/test/logs/stdout\",\"receiveTimestamp\":\"2026-03-09T08:20:46.852786133Z\",\"resource\":{\"labels\":{\"cluster_name\":\"cluster-primary\",\"container_name\":\"app\",\"location\":\"europe-west1\",\"namespace_name\":\"connector\",\"pod_name\":\"test-integration-eu-3-3-0-1111111111-hq6kl\",\"project_id\":\"test\"},\"type\":\"k8s_container\"},\"severity\":\"INFO\",\"timestamp\":\"2026-03-09T08:20:43.016224684Z\"}",
    "event": {
        "category": [
            "process"
        ],
        "reason": "\"{1: 1}\"",
        "type": [
            "change"
        ]
    },
    "@timestamp": "2026-03-09T08:20:43.016224Z",
    "cloud": {
        "project": {
            "id": "test"
        }
    },
    "google_kubernetes_engine": {
        "insertId": "1111111111111111",
        "logName": "projects/test/logs/stdout",
        "receiveTimestamp": "2026-03-09T08:20:46.852786133Z",
        "severity": "INFO"
    },
    "orchestrator": {
        "cluster": {
            "name": "cluster-primary"
        },
        "namespace": "connector",
        "resource": {
            "name": "test-integration-eu-3-3-0-1111111111-hq6kl",
            "type": "k8s_container"
        },
        "type": "kubernetes"
    },
    "server": {
        "geo": {
            "name": "europe-west1"
        }
    }
}
```
{% endcode %}
{% endtab %}
{% tab title="stdout_event_2.json" %}

{% code overflow="wrap" expandable="true" %}
```json
{
    "message": "{\"insertId\":\"1111111111111111\",\"jsonPayload\":{\"hostName\":\"host-name\",\"loggerName\":\"logger.test.Integration\",\"mdc\":{\"messageId\":\"11111111111111111\",\"subscription\":\"projects/test/subscriptions/integration\"},\"message\":\"Received message 11111111111111111\",\"ndc\":\"\",\"sequence\":22068,\"threadId\":156,\"threadName\":\"Thread\",\"timestamp\":\"2026-03-09T08:48:59.658400674Z\"},\"labels\":{\"compute.googleapis.com/resource_name\":\"resource-name\",\"k8s-pod/app_kubernetes_io/managed-by\":\"Manager\",\"k8s-pod/app_kubernetes_io/name\":\"inference-consumer\",\"k8s-pod/app_kubernetes_io/version\":\"1.10.0\",\"k8s-pod/manager_sh/chart\":\"app-0.1.0\",\"k8s-pod/pod-template-hash\":\"789754fc8f\",\"logging.gke.io/top_level_controller_name\":\"inference-consumer\",\"logging.gke.io/top_level_controller_type\":\"Deployment\"},\"logName\":\"projects/test/logs/stdout\",\"receiveTimestamp\":\"2026-03-09T08:49:02.892865366Z\",\"resource\":{\"labels\":{\"cluster_name\":\"cluster\",\"container_name\":\"app\",\"location\":\"europe-west1\",\"namespace_name\":\"inference\",\"pod_name\":\"host-name\",\"project_id\":\"test\"},\"type\":\"k8s_container\"},\"severity\":\"DEBUG\",\"timestamp\":\"2026-03-09T08:48:59.658510174Z\"}",
    "event": {
        "category": [
            "process"
        ],
        "reason": "\"Received message 11111111111111111\"",
        "type": [
            "change"
        ]
    },
    "@timestamp": "2026-03-09T08:48:59.658510Z",
    "cloud": {
        "project": {
            "id": "test"
        }
    },
    "google_kubernetes_engine": {
        "insertId": "1111111111111111",
        "logName": "projects/test/logs/stdout",
        "receiveTimestamp": "2026-03-09T08:49:02.892865366Z",
        "severity": "DEBUG"
    },
    "orchestrator": {
        "cluster": {
            "name": "cluster"
        },
        "namespace": "inference",
        "resource": {
            "name": "host-name",
            "type": "k8s_container"
        },
        "type": "kubernetes"
    },
    "server": {
        "geo": {
            "name": "europe-west1"
        }
    }
}
```
{% endcode %}
{% endtab %}
{% endtabs %}
