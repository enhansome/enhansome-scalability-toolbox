# Awesome Index with stars

[Diagrams](#diagrams) <br>
[API documentation](#api-documentation) <br>
[Message queues](#message-queues) <br>
[Load balancers, reverse proxy, accelerators, web servers](#load-balancers-reverse-proxy-accelerators-web-servers) <br>
[Service mesh](#service-mesh) <br>
[API Gateway](#api-gateway) <br>
[Structured and unstructured data storage](#structured-and-unstructured-data-storage) <br>
[Distributed consensus management, service discovery and configuration](#distributed-consensus-management-service-discovery-and-configuration) <br>
[CRDT and Operational transformation](#crdt-and-operational-transformation) <br>
[Infrastructure provisioning](#Infrastructure-provisioning) <br>
[Containers](#containers) <br>
[Kubernetes](#kubernetes) <br>
[Jsonnet](#jsonnet) <br>
[RPC, Communication between system nodes](#rpc-communication-between-system-nodes) <br>
[gRPC](#grpc) <br>
[Service monitoring, metrics collection / graphing](#service-monitoring-metrics-collection--graphing) <br>
[Infrastructure information management](#infrastructure-information-management) <br>
[Distributed request tracing](#distributed-request-tracing) <br>
[Load testing](#load-testing) <br>
[Log management](#log-management) <br>
[Feature Flags](#feature-flags) <br>
[Deployment tools](#deployment-tools) <br>
[CI (Continuous Integration)](#ci-continuous-integration) <br>
[CDNs](#cdns) <br>
[Domain registrars](#domain-registrars) <br>
[AWS](#aws) <br>
[Networking](#networking) <br>
[SDN](#sdn) <br>
[SRE (Site Reliability Engineering)](#sre-site-reliability-engineering) <br>
[Disk storage](#disk-storage) <br>
[TLS](#tls) <br>
[HTTP/3 and QUIC](#http3-and-quic) <br>
[Authorization and Authentication](#authorization-and-authentication) <br>
[Cryptography](#cryptography) <br>
[UUID](#uuid) <br>
[Hashing](#hashing) <br>
[Videos](#videos) <br>
[Real User Monitoring](#real-user-Monitoring) <br>
[QA Automation](#qa-automation) <br>
[Tools](#tools) <br>
[Misc](#misc) <br>

# Diagrams

[PlantUML](https://plantuml.com/) <br>
[Mermaid](https://mermaidjs.github.io/) <br>
[C4 (multi-level architecture diagrams)](https://c4model.com/) <br>
[Structurizr (multi-level DSL)](https://structurizr.com/) <br>
[IcePanel (multi-level modelling and diagrams)](https://icepanel.io/) <br>
[dbdiagrams (DB ERD)](https://dbdiagram.io/) <br>
[Workload Discovery on AWS](https://aws.amazon.com/solutions/implementations/workload-discovery-on-aws/) <br>
[Cloudcraft (AWS only)](https://cloudcraft.co/) <br>
[vega (visualization from JSON)](https://github.com/vega/vega) ⭐ 11,957 | 🐛 469 | 🌐 JavaScript | 📅 2026-08-14 and [vega light](https://github.com/vega/vega-lite) ⭐ 5,447 | 🐛 817 | 🌐 TypeScript | 📅 2026-08-14 <br>
[arc42](https://arc42.org/) <br>

# API documentation

[OpenAPI](https://www.openapis.org/) <br>
[Swagger](https://swagger.io/) <br>
[Wording](https://www.ietf.org/rfc/rfc2119.txt), [definition syntax](https://www.ietf.org/rfc/rfc5234.txt) and [units](http://unitsofmeasure.org/ucum.html) for RFC specification creation <br>
[API Stylebook](http://apistylebook.com/) <br>
[Spectral (API linter)](https://github.com/stoplightio/spectral) ⭐ 3,180 | 🐛 274 | 🌐 TypeScript | 📅 2026-08-13 <br>
[Dredd (API tester)](https://github.com/apiaryio/dredd) ⚠️ Archived <br>
[Zally (API linter)](https://github.com/zalando/zally) ⭐ 946 | 🐛 101 | 🌐 Kotlin | 📅 2026-07-08 <br>
[GraphQL](https://graphql.org/), [UI client](https://altair.sirmuel.design/) <br>

# Message queues

Real-time (<1ms): [Aeron](https://github.com/real-logic/Aeron) ⭐ 8,788 | 🐛 22 | 🌐 Java | 📅 2026-08-14, [Chronicle Queue](https://github.com/OpenHFT/Chronicle-Queue) ⭐ 3,791 | 🐛 38 | 🌐 Java | 📅 2026-08-12 <br>
Brokerless: [ZeroMQ](http://zeromq.org/), [nanomsg](http://nanomsg.org/), [NSQ](https://nsq.io/), [nng](https://github.com/nanomsg/nng) ⭐ 4,654 | 🐛 66 | 🌐 C | 📅 2026-08-02 <br>
[Kafka](https://kafka.apache.org/), Kafka Web UI solutions: [AKHQ](https://github.com/tchiotludo/akhq) ⭐ 3,844 | 🐛 270 | 🌐 Java | 📅 2026-08-12, [Kafdrop](https://github.com/obsidiandynamics/kafdrop) ⭐ 6,155 | 🐛 51 | 🌐 Java | 📅 2026-08-11, [Kowl](https://github.com/cloudhut/kowl) ⭐ 4,317 | 🐛 152 | 🌐 TypeScript | 📅 2026-08-14, [Lenses Box](https://github.com/lensesio/fast-data-dev) ⭐ 2,080 | 🐛 81 | 🌐 Shell | 📅 2025-11-20 <br>
[Redpanda (Kafka compatible)](https://github.com/redpanda-data/redpanda/) ⭐ 12,443 | 🐛 617 | 🌐 C++ | 📅 2026-08-15 <br>
[RabbitMQ](https://www.rabbitmq.com/) <br>
[Pulsar](https://pulsar.apache.org/) <br>
[RocketMQ](https://rocketmq.apache.org/) <br>
[MemQ (thoughput optimized)](https://github.com/pinterest/memq) ⭐ 141 | 🐛 10 | 🌐 Java | 📅 2026-08-10 <br>
[NATS](https://nats.io/) <br>

# Load balancers, reverse proxy, accelerators, web servers

[HAProxy](http://www.haproxy.org/), [Unofficial Web UI](https://github.com/Aidaho12/haproxy-wi) ⭐ 1,815 | 🐛 7 | 🌐 Python | 📅 2026-08-04 <br>
[Envoy](https://www.envoyproxy.io/) and [Dropbox migration to Envoy from nginx](https://dropbox.tech/infrastructure/how-we-migrated-dropbox-from-nginx-to-envoy) <br>
[nginx](https://www.nginx.com/), [nginx config](https://nginxconfig.io/) <br>
[OpenResty](https://openresty.org/en/) <br>
[Varnish](https://varnish-cache.org/) <br>
[Tomcat](https://tomcat.apache.org/) <br>
[Træfik](https://traefik.io/) <br>
[Tarantool (mail.ru)](https://tarantool.org/) <br>
[lightttpd](https://www.lighttpd.net/) <br>
[katran (BPF/XDP L4LB, Facebook)](https://github.com/facebookincubator/katran) ⭐ 5,293 | 🐛 2 | 🌐 C | 📅 2026-08-14 <br>
[GLB Director (DPDK L4LB, Github)](https://github.com/github/glb-director) ⭐ 2,448 | 🐛 32 | 🌐 C | 📅 2026-08-14 <br>
[Cloudflare Unimog design](https://blog.cloudflare.com/unimog-cloudflares-edge-load-balancer/) <br>

# Service mesh

[Linkerd](https://linkerd.io/) <br>
[Envoy](https://www.envoyproxy.io/) <br>
[Envoy introduction](https://www.youtube.com/watch?v=RVZX4CwKhGE) <br>
[Learn Envoy](https://www.learnenvoy.io/) <br>
[Consul Connect](https://www.consul.io/docs/connect) <br>
[Kuma (from Kong)](https://kuma.io/) <br>
[Kong Mesh](https://konghq.com/kong-mesh) <br>
[xDS control protocol](https://github.com/cncf/xds) ⭐ 271 | 🐛 31 | 🌐 Starlark | 📅 2026-03-09 <br>
[Rotor (xDS, Turbine Labs)](https://github.com/turbinelabs/rotor) ⭐ 306 | 🐛 3 | 🌐 Go | 📅 2019-08-08 <br>
[ModSecurity for Envoy (WAF)](https://github.com/octarinesec/ModSecurity-envoy) ⚠️ Archived <br>
[Envoy Java control plane](https://github.com/envoyproxy/java-control-plane) ⭐ 312 | 🐛 61 | 🌐 Java | 📅 2026-08-10 <br>
[Istio service mesh controller](https://istio.io/) <br>
[Istio introduction](https://www.youtube.com/watch?v=s4qasWn_mFc) <br>
[Conduit (Rust, linkerd devs)](https://conduit.io/) <br>
[Netflix Vizceral (observability)](https://github.com/Netflix/vizceral) ⭐ 4,094 | 🐛 54 | 🌐 JavaScript | 📅 2023-11-28 <br>
[Kiali (observability, Istio)](https://kiali.org) <br>
[Vistio (observability, Istio)](https://github.com/nmnellis/vistio) ⭐ 371 | 🐛 5 | 🌐 JavaScript | 📅 2018-10-20 <br>

# API Gateway

[AWS API Gateway](https://aws.amazon.com/api-gateway/) <br>
[Kong](https://konghq.com/kong) <br>
[Cloudflare API Gateway](https://blog.cloudflare.com/api-gateway/) <br>
[KrakenD](https://www.krakend.io/) <br>

# Structured and unstructured data storage

[DynamoDB](https://aws.amazon.com/dynamodb/) and it's [internal design (2022)](https://www.usenix.org/system/files/atc22-elhemali.pdf) <br>
[PostgreSQL](https://www.postgresql.org/) <br>
[Postgres Pro (PostgreSQL)](https://postgrespro.ru/) <br>
[RDS Postgres vs Aurora Postgres 13](https://www.migops.com/blog/2021/11/26/is-aurora-postgresql-really-faster-and-cheaper-than-rds-postgresql-benchmarking/) <br>
[MySQL](https://www.mysql.com/), [ProxySQL (for MySQL)](https://proxysql.com/), [mydumper (MySQL multi-threaded backup/restore)](https://github.com/maxbube/mydumper) ⭐ 3,208 | 🐛 57 | 🌐 C | 📅 2026-08-11 <br>
[RocksDB (InnoDB replacement by Facebook)](http://myrocks.io/), [Using NVM in Facebook (RocksDB)](https://dl.acm.org/citation.cfm?id=3190524) <br>
[Vitess (MySQL auto horizontal scaling)](http://vitess.io/) <br>
[MariaDB (MySQL)](https://mariadb.com/) <br>
[Percona (MySQL)](https://www.percona.com/) <br>
[MongoDB](https://www.mongodb.com/) <br>
[Scylla (Cassandra done right)](http://www.scylladb.com/), [ScyllaDB with Optane](https://www.scylladb.com/2017/08/08/intel-optane-review/) <br>
[Cassandra](https://cassandra.apache.org/) <br>
[CockroachDB](https://www.cockroachlabs.com/) <br>
[Aerospike](http://www.aerospike.com/) <br>
[FoundationDB](https://www.foundationdb.org/) <br>
[TiDB](https://docs.pingcap.com/tidb/stable/overview) <br>
[JSON in Postgre 10.x, 11.x, PostgreSQL 9.6 vs Mongo 3.4](https://www.youtube.com/watch?v=SNzOZKvFZ68) <br>
[Why Uber Engineering Switched from Postgres to MySQL](https://eng.uber.com/mysql-migration/) and [Follow up 1](https://www.slideshare.net/AlexanderKorotkov/our-answer-to-uber/), [2](https://blog.2ndquadrant.com/thoughts-on-ubers-list-of-postgres-limitations/), [3](http://thebuild.com/presentations/uber-perconalive-2017.pdf), [4](https://rhaas.blogspot.gr/2016/08/ubers-move-away-from-postgresql.html), [5](https://devconf.ru/ru/archive/devconf2017/offer/314), [6](https://habr.com/company/devconf/blog/353682/), [7](https://use-the-index-luke.com/blog/2016-07-29/on-ubers-choice-of-databases) <br>
[Redis](https://redis.io/), [Community Slack Channel](https://rediscommunity.slack.com/) <br>
Redis modules: [5 open source modules](https://goodformcode.com/), [JSON module](https://github.com/RedisJSON/RedisJSON) ⭐ 3,951 | 🐛 176 | 🌐 Rust | 📅 2026-08-09 <br>
Redis UI: [RedisInsight](https://redislabs.com/redisinsight/), [AnotherRedisDesktopManager](https://github.com/qishibo/AnotherRedisDesktopManager) ⭐ 34,633 | 🐛 158 | 🌐 JavaScript | 📅 2026-08-13, [Redis-UI](https://github.com/patrikx3/redis-ui/) ⭐ 805 | 🐛 1 | 🌐 JavaScript | 📅 2026-06-29, [Redis Desktop Manager](https://github.com/uglide/RedisDesktopManager) ⭐ 23,225 | 🐛 70 | 🌐 C++ | 📅 2024-07-10 <br>
[iredis (improved CLI for Redis)](https://github.com/laixintao/iredis/) ⭐ 2,740 | 🐛 50 | 🌐 Python | 📅 2026-07-27 <br>
[KeyDB (Redis fork with I/O multithreading and offloading to flash)](https://keydb.dev/) <br>
[Memcached](https://github.com/memcached/memcached/) ⭐ 14,250 | 🐛 102 | 🌐 C | 📅 2026-07-10, [extstore storage shim](https://github.com/memcached/memcached/wiki/Extstore) ⭐ 14,250 | 🐛 102 | 🌐 C | 📅 2026-07-10, [Caching beyond RAM: the case for NVMe](https://memcached.org/blog/nvm-caching/) <br>
[Memcached-SR with BMC(BPF Memory Cache)](https://github.com/Orange-OpenSource/bmc-cache) ⭐ 464 | 🐛 11 | 🌐 C | 📅 2021-09-24 and it's [paper with video](https://pchaigno.github.io/ebpf/2021/04/12/bmc-accelerating-memcached-using-bpf-and-xdp.html) <br>
[Segcache (in-memory storage optimized for small objects with short TTL, Twitter)](https://github.com/Thesys-lab/Segcache) ⭐ 121 | 🐛 2 | 🌐 C | 📅 2023-05-15 <br>
[FASTER (Microsoft)](https://github.com/Microsoft/FASTER) ⭐ 6,636 | 🐛 35 | 🌐 C# | 📅 2026-08-13, [official site](https://www.microsoft.com/en-us/research/project/FASTER/) <br>
[Anna (experimental, Berkeley RISE Lab)](https://github.com/fluent-project/fluent/tree/master/kvs) ⚠️ Archived, [white paper](https://arxiv.org/abs/1809.00089) <br>
[LogDevice (Facebook, distributed storage for sequential data)](https://github.com/facebookincubator/LogDevice) ⚠️ Archived <br>
[OrientDB (graph)](https://orientdb.com/) <br>
[Database isolation levels](https://en.wikipedia.org/wiki/Isolation_\(database_systems\)) <br>
[The Log-Structured Merge-Tree (LSM-Tree) whitepaper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.44.2782\&rep=rep1\&type=pdf) <br>
[B+ tree](https://en.wikipedia.org/wiki/B%2B_tree) <br>
[YCSB (Yahoo! Cloud Serving Benchmark)](https://github.com/brianfrankcooper/YCSB) ⭐ 5,232 | 🐛 383 | 🌐 Java | 📅 2026-08-12 <br>

# Distributed consensus management, service discovery and configuration

[Raft protocol](https://raft.github.io/) <br>
[Paxos protocol](https://en.wikipedia.org/wiki/Paxos_\(computer_science\)) <br>
[Paxos made simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf) <br>
[Paxos Made Live - An Engineering Perspective](http://www.read.seas.harvard.edu/~kohler/class/08w-dsi/chandra07paxos.pdf) <br>
[Consul](https://www.consul.io/) <br>
[etcd](https://coreos.com/etcd/) <br>
[Vault](https://www.vaultproject.io/) <br>
[Secure Production Identity Framework For Everyone (SPIFFE)](https://github.com/spiffe/spiffe) ⭐ 1,824 | 🐛 49 | 🌐 Shell | 📅 2026-08-03 <br>
[ZooKeeper](https://zookeeper.apache.org/) <br>

# CRDT and Operational transformation

<b>Operational Transformation</b> <br>
White papers: [Original Jupiter document (1995)](https://dl.acm.org/doi/pdf/10.1145/215585.215706), [Jupiter Made Abstract, and Then Refined (2020)](https://hengxin.github.io/papers/2020-JCST-Jupiter.pdf) <br>
Libraries: [sharedb](https://github.com/share/sharedb) ⭐ 6,538 | 🐛 156 | 🌐 JavaScript | 📅 2026-07-31, [ottypes](https://github.com/orgs/ottypes/repositories), [libot](https://github.com/ottypes/libot) ⭐ 113 | 🐛 0 | 🌐 C | 📅 2015-07-30 <br>
Articles: [Collaborative Editing in CodeMirror](https://marijnhaverbeke.nl/blog/collaborative-editing-cm.html) <br> <b>CRDT</b> <br>
Libraries: [Automerge](https://github.com/automerge/automerge) ⭐ 6,503 | 🐛 111 | 🌐 JavaScript | 📅 2026-08-12, [Yjs](https://github.com/yjs/yjs) ⭐ 22,354 | 🐛 135 | 🌐 JavaScript | 📅 2026-08-06, [Diamond Types (speed oriented)](https://github.com/josephg/diamond-types) ⭐ 1,829 | 🐛 19 | 🌐 Rust | 📅 2026-07-31, [Reference CRTS implementation](https://github.com/josephg/reference-crdts) ⭐ 142 | 🐛 0 | 🌐 TypeScript | 📅 2023-12-01, [Yjs (port to Rust)](https://github.com/y-crdt/y-crdt) ⭐ 2,142 | 🐛 112 | 🌐 Rust | 📅 2026-08-08, [teletype (Atom, deprecated)](https://github.com/atom/teletype-crdt) ⚠️ Archived <br>
[CRDT benchmarking](https://github.com/dmonad/crdt-benchmarks) ⭐ 537 | 🐛 6 | 🌐 JavaScript | 📅 2024-04-29 <br>
[Collection of whitepapers and articles](https://github.com/alangibson/awesome-crdt) ⭐ 1,397 | 🐛 0 | 📅 2026-07-28 <br>

# Infrastructure provisioning

[Terraform](https://www.terraform.io/) <br>
[Terragrunt](https://terragrunt.gruntwork.io/) <br>
[Terraform best practices](https://www.terraform-best-practices.com/) <br>
[Terraform AWS modules](https://github.com/terraform-aws-modules) <br>
[Infracost - calculate Terraform deployment costs (AWS)](https://github.com/infracost/infracost) ⭐ 12,449 | 🐛 24 | 🌐 Go | 📅 2026-08-11 <br>
[modules.tf - Convert Cloudcraft diagrams to Terraform code](https://modules.tf/) <br>
[Pulumi](https://www.pulumi.com/) <br>
[Crossplain](https://crossplane.io/) <br>

# Deployment tools

[Ansible](https://ansible.com/) <br>
[Teletraan](https://github.com/pinterest/teletraan) ⭐ 1,834 | 🐛 78 | 🌐 Java | 📅 2026-08-14 <br>

# CI (Continuous Integration)

[Github Actions](https://github.com/features/actions) <br>
[TeamCity](https://www.jetbrains.com/teamcity) <br>
[Jenkins](https://jenkins.io) <br>
[Jenkins X (for k8s apps)](https://jenkins-x.io/) <br>
[JetBrains Space](https://www.jetbrains.com/space/) <br>
[Tekton Pipelines (k8s native using CRD)](https://tekton.dev/) <br>

# Containers

[Docker](https://www.docker.com/) <br>
Docker Registries: [Harbor](https://goharbor.io/), [Quay](https://github.com/quay/quay) ⭐ 2,818 | 🐛 303 | 🌐 Python | 📅 2026-08-15 <br>
[Awesome Docker list](https://github.com/veggiemonk/awesome-docker) ⭐ 36,641 | 🐛 25 | 📅 2026-07-29 <br>
[docker-autoheal (restart on unhealthy event)](https://github.com/willfarrell/docker-autoheal) ⭐ 1,983 | 🐛 62 | 🌐 Shell | 📅 2025-09-09 <br>
[Kubernetes](https://kubernetes.io/) <br>
[Container Network Interface](https://github.com/containernetworking/cni) ⭐ 6,070 | 🐛 155 | 🌐 Go | 📅 2026-08-13 <br>
[Mesosphere](https://mesosphere.com/) <br>
[Mesos](https://mesos.apache.org/) <br>
[gVisor (sandbox runtime)](https://github.com/google/gvisor) ⭐ 19,087 | 🐛 777 | 🌐 Go | 📅 2026-08-15 <br>
[Weave Scope (monitoring)](https://github.com/weaveworks/scope) ⭐ 5,908 | 🐛 455 | 🌐 Go | 📅 2023-07-07 <br>
[SysDig (monitoring)](https://github.com/draios/sysdig) ⭐ 8,283 | 🐛 116 | 🌐 C++ | 📅 2026-04-13 <br>

# Kubernetes

[Lens (k8s IDE)](https://github.com/lensapp/lens) ⭐ 23,215 | 🐛 1,169 | 📅 2025-02-11 <br>
[k9s (alternative cli)](https://github.com/derailed/k9s) ⭐ 34,353 | 🐛 111 | 🌐 Go | 📅 2026-08-14 <br>
[minikube](https://minikube.sigs.k8s.io/) <br>
[kubectl](https://kubernetes.io/docs/reference/kubectl/overview/) <br>
[Krew (kubectl plugin manager)](https://krew.dev/), [list of plugins](https://github.com/kubernetes-sigs/krew-index/blob/master/plugins.md) ⭐ 693 | 🐛 12 | 📅 2026-08-14 <br>
[kustomize](https://github.com/kubernetes-sigs/kustomize) ⭐ 12,134 | 🐛 194 | 🌐 Go | 📅 2026-08-12 <br>
[Helm](https://helm.sh/) <br>
[Knative (run serverless apps on top of Istio](https://knative.dev/) <br>
[List of K8s application management tools](https://docs.google.com/spreadsheets/d/1FCgqz1Ci7_VCz_wdh8vBitZ3giBtac_H8SBw4uxnrsE/edit#gid=0) <br>
[Kompose (Docker Compose to k8s)](http://kompose.io/) <br>
[ksonnet](https://ksonnet.io/) <br>
[kubecfg](https://github.com/ksonnet/kubecfg) ⚠️ Archived <br>
[Skaffold](https://github.com/GoogleCloudPlatform/skaffold) ⭐ 15,887 | 🐛 907 | 🌐 Go | 📅 2026-08-10 <br>
[Draft](https://github.com/Azure/draft) ⭐ 642 | 🐛 24 | 🌐 Go | 📅 2026-08-07 <br>
[Kubespray (cluster setup)](https://kubespray.io/) <br>
[kops (cluster setup)](https://github.com/kubernetes/kops) ⭐ 16,662 | 🐛 128 | 🌐 Go | 📅 2026-08-15 <br>
[kubectx & kubens (switch clusters and namespaces](https://github.com/ahmetb/kubectx) ⭐ 19,939 | 🐛 39 | 🌐 Go | 📅 2026-08-02 <br>
[goldpinger (nodes connectivity test/display](https://github.com/bloomberg/goldpinger) ⭐ 2,731 | 🐛 36 | 🌐 JavaScript | 📅 2026-04-23 <br>
[kube-ps1 (bash prompt)](https://github.com/jonmosco/kube-ps1) ⭐ 3,806 | 🐛 5 | 🌐 Shell | 📅 2026-05-24 <br>
[stern (pod and container logs tailing)](https://github.com/wercker/stern) <br>
[click (cli for large clusters)](https://github.com/databricks/click) ⭐ 1,506 | 🐛 39 | 🌐 Rust | 📅 2026-03-27 <br>
[Telepresence (for k8s services development)](https://www.telepresence.io/) <br>
[Cilium](https://github.com/cilium/cilium) ⭐ 24,927 | 🐛 1,085 | 🌐 Go | 📅 2026-08-14 <br>
[Calico](https://www.projectcalico.org) <br>
[AWS VPC Kubernetes CNI driver using IPvlan](https://github.com/lyft/cni-ipvlan-vpc-k8s) ⭐ 365 | 🐛 15 | 🌐 Go | 📅 2023-08-30 <br>
[Contour (Ingress controller using Envoy)](https://github.com/heptio/contour) ⭐ 3,943 | 🐛 121 | 🌐 HTML | 📅 2026-08-12 <br>
[Gimbal (Ingress load balancer to many clusters)](https://github.com/heptio/gimbal) ⚠️ Archived <br>
[Vault with Kubernetes](https://github.com/Boostport/kubernetes-vault) ⚠️ Archived and [Video on improvements](https://www.youtube.com/watch?v=IulNdGlQR3A) <br>
[Weave Scope (Monitoring, visualisation & management for k8s)](https://github.com/weaveworks/scope/) ⭐ 5,908 | 🐛 455 | 🌐 Go | 📅 2023-07-07 <br>
[Guide to Kubernetes networking (part 1)](https://medium.com/@ApsOps/an-illustrated-guide-to-kubernetes-networking-part-1-d1ede3322727), [Part 2](https://medium.com/@ApsOps/an-illustrated-guide-to-kubernetes-networking-part-2-13fdc6c4e24c) <br>
[Kubernetes Security - Best Practice Guide](https://github.com/freach/kubernetes-security-best-practice) ⭐ 2,706 | 🐛 12 | 📅 2019-09-11 <br>
[RBAC and user managemenet generation using Web UI](https://github.com/sighupio/permission-manager) ⭐ 1,373 | 🐛 34 | 🌐 TypeScript | 📅 2024-05-12 <br>
[Chaos mesh](https://github.com/pingcap/chaos-mesh) ⭐ 7,843 | 🐛 542 | 🌐 Go | 📅 2026-08-07 <br>

# Jsonnet

[jsonnet](http://jsonnet.org/) <br>
[jsonnet builds](https://github.com/krootee/jsonnet-releases) ⭐ 0 | 🐛 0 | 📅 2018-07-04 <br>
[Visual Studio Code plugin](https://github.com/heptio/vscode-jsonnet) ⚠️ Archived <br>
[IntelliJ plugin (alpha)](https://github.com/databricks/intellij-jsonnet) ⭐ 91 | 🐛 15 | 🌐 Java | 📅 2024-03-09 <br>
[Style guide (Databricks)](https://github.com/databricks/jsonnet-style-guide) ⭐ 234 | 🐛 8 | 📅 2023-04-28 <br>

# RPC, Communication between system nodes

[gRPC](https://grpc.io/) <br>
[Dubbo (China version of gRPC)](https://dubbo.apache.org) <br>
[Protocol Buffers](https://developers.google.com/protocol-buffers/) <br>
[Thrift](https://thrift.apache.org/) <br>
[Cap'n Proto](https://capnproto.org/) <br>
[MessagePack](https://msgpack.org/) <br>
[FlatBuffers](https://google.github.io/flatbuffers/) <br>
[Motan](https://github.com/weibocom/motan) ⭐ 5,873 | 🐛 364 | 🌐 Java | 📅 2025-11-24 <br>
[Aeron](https://github.com/real-logic/aeron) ⭐ 8,788 | 🐛 22 | 🌐 Java | 📅 2026-08-14 <br>
[ZeroMQ](http://zeromq.org/) <br>
[SMF](https://github.com/senior7515/smf) ⭐ 21 | 🐛 0 | 🌐 C++ | 📅 2019-11-03 <br>

# gRPC

[Awesome gRPC list](https://github.com/grpc-ecosystem/awesome-grpc) ⭐ 8,345 | 🐛 26 | 📅 2025-10-28 <br>
[gRPC status codes](https://github.com/grpc/grpc/blob/master/doc/statuscodes.md) ⭐ 45,286 | 🐛 1,378 | 🌐 C++ | 📅 2026-08-15 <br>
[gRPC Field Mask](https://developers.google.com/protocol-buffers/docs/reference/csharp/class/google/protobuf/well-known-types/field-mask) and Netflix guide to using it [Get operations](https://netflixtechblog.com/practical-api-design-at-netflix-part-1-using-protobuf-fieldmask-35cfdc606518) and [Update operations](https://netflixtechblog.com/practical-api-design-at-netflix-part-2-protobuf-fieldmask-for-mutation-operations-2e75e1d230e4) <br>
[gRPC field presence (v3.15+)](https://github.com/protocolbuffers/protobuf/blob/master/docs/field_presence.md) ⭐ 71,730 | 🐛 305 | 🌐 C++ | 📅 2026-08-15 <br>
[Insomnia (test client)](https://insomnia.rest/) <br>
[Postman (test client)](https://www.postman.com/) <br>
[Hoppscotch (test client)](https://hoppscotch.io/) <br>
[Kreay (test client)](https://kreya.app/) <br>
[httpYac (test client)](https://httpyac.github.io/) <br>
[milkman test client (via gRPC plugin)](https://github.com/warmuuh/milkman) ⭐ 1,340 | 🐛 16 | 🌐 Java | 📅 2026-08-04 <br>
[improbabl test client (Web)](https://github.com/improbable-eng/grpc-web/) ⭐ 4,473 | 🐛 180 | 🌐 TypeScript | 📅 2023-09-23 <br>
[bloomrpc test client (GUI)](https://github.com/uw-labs/bloomrpc) ⚠️ Archived <br>
[gRPC 2 years in production](https://www.youtube.com/watch?v=7FZ6ZyzGex0) <br>

# Service monitoring, metrics collection / graphing

[Grafana](https://grafana.com/) <br>
[Grafonnet-lib (generate dashboards for Grafana)](https://github.com/grafana/grafonnet-lib) ⚠️ Archived <br>
[Graphite](https://graphiteapp.org/) <br>
[Prometheus](https://prometheus.io/) <br>
[Thanos (Prometheus long term storage)](https://thanos.io/) <br>
[Cortex (Prometheus long term storage)](https://cortexmetrics.io/) <br>
[OpenMetrics](https://github.com/OpenObservability/OpenMetrics) ⭐ 2,535 | 🐛 30 | 🌐 Go | 📅 2026-07-19 <br>
[eBPF exporter (Prometheus)](https://github.com/cloudflare/ebpf_exporter) ⭐ 2,627 | 🐛 17 | 🌐 Go | 📅 2026-08-03 <br>
[Node Exporter (Prometheus)](https://github.com/prometheus/node_exporter) ⭐ 13,698 | 🐛 322 | 🌐 Go | 📅 2026-08-08 <br>
[cAdvisor (container monitoring)](https://github.com/google/cadvisor) ⭐ 19,357 | 🐛 66 | 🌐 Go | 📅 2026-07-20 <br>
[ClichHouse (Yandex)](https://clickhouse.yandex/) <br>
[Druid (Imply)](http://druid.io/) <br>
[Pinot (Linkedin)](https://github.com/linkedin/pinot/) <br>
[Architecture analysis of ClickHouse, Druid and Pinot](https://medium.com/@leventov/comparison-of-the-open-source-olap-systems-for-big-data-clickhouse-druid-and-pinot-8e042a5ed1c7) <br>
[HTTP Analytics for 6M requests per second using ClickHouse](https://blog.cloudflare.com/http-analytics-for-6m-requests-per-second-using-clickhouse/) <br>
[NetData](https://my-netdata.io) <br>
[Vector (host monitoring)](http://getvector.io/) <br>
[okmeter](https://okmeter.io) <br>
[Datadog](https://www.datadoghq.com) <br>
[TimescaleDB](https://github.com/timescale/timescaledb) ⭐ 23,333 | 🐛 382 | 🌐 C | 📅 2026-08-14 <br>
[KairosDB](https://kairosdb.github.io) <br>
[Zabbix](https://www.zabbix.com) <br>
[PagerDuty](https://www.pagerduty.com) <br>

# Infrastructure information management

[Osquery (Facebook)](https://osquery.io/) <br>
[Kolide Fleet (osquery)](http://www.kolide.co/fleet) <br>
[Doorman (osquery)](https://github.com/mwielgoszewski/doorman) ⭐ 621 | 🐛 29 | 🌐 Python | 📅 2022-12-08 <br>
[OSSEC](https://ossec.github.io/) <br>

# Distributed request tracing

[Dapper, a Large-Scale Distributed Systems Tracing Infrastructure (Google)](https://research.google.com/pubs/pub36356.html) <br>
[OpenTelemetry](https://opentelemetry.io/) <br>
[OpenTracing and Jaeger introduction](https://www.youtube.com/watch?v=fjYAU3jayVo) <br>
[TraceContext propagation format](https://github.com/w3c/distributed-tracing) ⭐ 510 | 🐛 27 | 🌐 Python | 📅 2026-06-29 <br>
[Jaeger (Uber)](https://www.jaegertracing.io/) <br>
[Zipkin](http://zipkin.io/) <br>
[Lightstep](https://lightstep.com) <br>
[Tempo (Grafana)](https://github.com/grafana/tempo) ⭐ 5,438 | 🐛 164 | 🌐 Go | 📅 2026-08-14 <br>
[Skywalking](http://skywalking.io/) <br>
[AWS X-Ray](https://aws.amazon.com/xray/) <br>

# Load testing

[Yandex.Tank (C++, Python, Go)](https://github.com/yandex/yandex-tank) ⭐ 2,596 | 🐛 84 | 🌐 Python | 📅 2026-08-14 <br>
[Overload (storage for Yandex.Tank results)](https://overload.yandex.net) <br>
[Gatling (Scala)](https://gatling.io/) <br>
[k6](https://github.com/loadimpact/k6) ⭐ 31,260 | 🐛 778 | 🌐 Go | 📅 2026-08-14 <br>
[Locust (Python)](https://locust.io/) <br>
[Vegeta (HTTP 1.1/2)](https://github.com/tsenart/vegeta) ⭐ 25,144 | 🐛 121 | 🌐 Go | 📅 2026-02-16 <br>
[h2load (HTTP 1.1/2)](https://nghttp2.org/documentation/h2load.1.html) <br>
[autocannon (HTTP 1.1)](https://github.com/mcollina/autocannon) ⭐ 8,490 | 🐛 58 | 🌐 JavaScript | 📅 2026-05-16 <br>

# Log management

[What you need to know about real-time logs](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) <br>
[Vector](https://github.com/timberio/vector) ⭐ 22,364 | 🐛 2,509 | 🌐 Rust | 📅 2026-08-15 <br>
[fluentd](https://www.fluentd.org/) <br>
[Logstash](https://www.elastic.co/products/logstash) <br>
[Graylog2](https://www.graylog.org/) <br>
[syslog-ng](https://syslog-ng.org/) <br>
[rsyslog](http://www.rsyslog.com/) <br>
[fluentbit](https://github.com/fluent/fluent-bit/) ⭐ 8,029 | 🐛 754 | 🌐 C | 📅 2026-08-15 <br>
[filebit](https://www.elastic.co/guide/en/beats/filebeat/master/filebeat-overview.html) <br>
[Kibana](https://www.elastic.co/kibana) <br>
[Loki](https://github.com/grafana/loki) ⭐ 28,735 | 🐛 1,767 | 🌐 Go | 📅 2026-08-14 <br>
[Splunk](https://www.splunk.com/) <br>
[GoAccess](https://goaccess.io/) <br>
[Bookkeeper](https://bookkeeper.apache.org/distributedlog/) <br>
[LogDevice (Facebook)](https://code.facebook.com/posts/357056558062811/logdevice-a-distributed-data-store-for-logs/) <br>
Online solutions: <br>
[Loggly](https://www.loggly.com/) <br>
[Logentries](https://logentries.com/) <br>
[Papertrail](https://papertrailapp.com/) <br>
[Scalyr](https://www.scalyr.com/) <br>
[Sumo Logic](https://www.sumologic.com/) <br>
[Humio](https://humio.com/) <br>

# Feature Flags

[Overview site](http://featureflags.io) <br>
[FF4J](http://ff4j.org/) <br>
[Togglz (Java)](https://www.togglz.org) <br>
[Unleash (simple)](https://github.com/Unleash/unleash) ⭐ 13,737 | 🐛 54 | 🌐 TypeScript | 📅 2026-08-14 <br>
[LaunchDarkly (cloud provider)](https://launchdarkly.com) <br>
[piranha (Uber tool to refactor feature flag code)](https://github.com/uber/piranha) ⭐ 2,466 | 🐛 68 | 🌐 Rust | 📅 2026-04-02 <br>

# CDNs

[Cloudflare](https://www.cloudflare.com/cdn/) <br>
[CloudFront (AWS)](https://aws.amazon.com/cloudfront/) <br>
[Fastly](https://www.fastly.com/) <br>
[Akamai](https://www.akamai.com/) <br>
[Traffic Control (Self-hosted CDN)](https://trafficcontrol.apache.org/) <br>

# Domain registrars

[MarkMonitor](https://www.markmonitor.com/) <br>
[Cloudflare](https://www.cloudflare.com/registrar/) <br>

# AWS

[AWS Infrastructure overview](https://www.infrastructure.aws/) <br>
[awscli](https://aws.amazon.com/cli/) <br>
[awless](https://github.com/wallix/awless) ⭐ 4,959 | 🐛 119 | 🌐 Go | 📅 2022-08-02 <br>
[S3 Browser](https://s3browser.com/) <br>
[CloudBerry S3 Explorer](https://www.cloudberrylab.com/explorer/amazon-s3.aspx) <br>
[Analyze S3 speed from your location](https://cloudharmony.com/speedtest-for-aws:s3) <br>
[Analyze AWS S3 and CloudFront logs](https://github.com/nagyv/s3stat) ⭐ 32 | 🐛 5 | 🌐 Python | 📅 2017-03-25 + [GoAccess](https://goaccess.io/) <br>
[EC2 instance cheat sheet](https://www.ec2instances.info/) <br>
[S3 meta information](https://github.com/whitfin/s3-meta) ⭐ 49 | 🐛 1 | 🌐 Rust | 📅 2021-01-30 <br>
[AWS DNS ALIAS record (vs CNAME)](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/resource-record-sets-choosing-alias-non-alias.html) <br>
[Understanding IAM](https://www.daan.fyi/writings/iam) <br>

# Networking

AWS Networking Fundamentals overview: [Networking Fundamentals](https://www.youtube.com/watch?v=hiKPPy584Mg), [Application networking foundations](https://www.youtube.com/watch?v=WcZwWuq6FTk), [PrivateLink](https://www.youtube.com/watch?v=20RxEzAXG9o), [Advanced VPC fundamentals](https://www.youtube.com/watch?v=cbUNbK8ZdA0) <br>
[Scalable Reliable Datagram (SRD is available via ENA in AWS instances)](https://ieeexplore.ieee.org/document/9167399) <br>
["Soft-unicast" for egress traffic](https://blog.cloudflare.com/cloudflare-servers-dont-own-ips-anymore/) <br>
Proxies primer: based on [HTTP Connect](https://blog.cloudflare.com/a-primer-on-proxies/) and [QUIC (MASQUE)](https://blog.cloudflare.com/unlocking-quic-proxying-potential/) <br>
[Streams support in modern browsers](https://streams.spec.whatwg.org/) and [Current browser support state](https://caniuse.com/streams) <br>
[Understanding all DNS records](https://www.netmeister.org/blog/dns-rrs.html) <br>
[Understanding cost of bandwidth](https://blog.cloudflare.com/the-relative-cost-of-bandwidth-around-the-world/), [AWS egress cost analysis](https://blog.cloudflare.com/aws-egregious-egress/) <br>
[Peering database](https://www.peeringdb.com/) <br>
[WebTransport protocol (improving on WebSockets and WebRTC use cases)](https://github.com/w3c/webtransport) ⭐ 986 | 🐛 23 | 🌐 Bikeshed | 📅 2026-07-27 <br>
[chrony (NTP)](https://chrony.tuxfamily.org/) and [Facebook measuring chrony vs ntpd](https://engineering.fb.com/production-engineering/ntp-service/) <br>
[BPF introduction](https://qmonnet.github.io/whirl-offload/2016/09/01/dive-into-bpf/) <br>
[XDP](https://www.iovisor.org/technology/xdp) <br>
[BPFd (remote BPF by Google)](https://github.com/joelagnel/bpfd) ⚠️ Archived <br>
[bpftrace (high-level langauge for writing eBPF programs)](https://github.com/iovisor/bpftrace) ⭐ 10,281 | 🐛 252 | 🌐 C++ | 📅 2026-08-14 <br>
[BCC (Tools for BPF-based Linux IO analysis, networking, monitoring, and more)](https://github.com/iovisor/bcc) ⭐ 22,616 | 🐛 1,065 | 🌐 C | 📅 2026-08-14 <br>
[How to achieve low latency with 10Gbps Ethernet (Cloudflare)](https://blog.cloudflare.com/how-to-achieve-low-latency/) <br>
[BBR: Congestion-based congestion control](https://blog.acolyer.org/2017/03/31/bbr-congestion-based-congestion-control/), [BBR, the new kid on the TCP block](https://blog.apnic.net/2017/05/09/bbr-new-kid-tcp-block/) <br>
[Making Linux TCP Fast](https://netdevconf.org/1.2/papers/bbr-netdev-1.2.new.new.pdf) <br>
[SYN packet handling in the wild (Cloudflare)](https://blog.cloudflare.com/syn-packet-handling-in-the-wild/) <br>
[How TCP backlog works in Linux](https://veithen.github.io/2014/01/01/how-tcp-backlog-works-in-linux.html) <br>
[Understanding TCP close states](https://benohead.com/tcp-about-fin_wait_2-time_wait-and-close_wait/) <br>
[Bind before connect](https://idea.popcount.org/2014-04-03-bind-before-connect/) <br>
[SYNC Cookies](https://www.giac.org/paper/gsec/2013/syn-cookies-exploration/103486) <br>
[On SO\_REUSEADDR and SO\_REUSEPORT](https://stackoverflow.com/questions/14388706/socket-options-so-reuseaddr-and-so-reuseport-how-do-they-differ-do-they-mean-t/14388707#14388707) <br>
[On Linux history of poll(), select() and epoll()](https://idea.popcount.org/2017-02-20-epoll-is-fundamentally-broken-12/), [More on Linux epoll](https://habr.com/post/416669/) <br>
[Monitoring and Tuning the Linux Networking Stack: Receiving Data](https://blog.packagecloud.io/eng/2016/06/22/monitoring-tuning-linux-networking-stack-receiving-data/) <br>
[Monitoring and Tuning the Linux Networking Stack: Sending Data](https://blog.packagecloud.io/eng/2017/02/06/monitoring-tuning-linux-networking-stack-sending-data/) <br>
[MIT's TCP ex Machina: Computer-Generated Congestion Control](http://web.mit.edu/remy/) <br>
[Introduction to modern network load balancing and proxying (Envoy)](https://blog.envoyproxy.io/introduction-to-modern-network-load-balancing-and-proxying-a57f6ff80236) <br>
[BGP in 2017](http://www.potaroo.net/ispcol/2018-01/bgp2017.html) <br>
[CoreDNS](https://github.com/coredns/coredns) ⭐ 14,246 | 🐛 302 | 🌐 Go | 📅 2026-08-15 <br>
[Knot DNS](https://gitlab.labs.nic.cz/knot/knot-dns) <br>
[Knot Resolver](https://gitlab.labs.nic.cz/knot/knot-resolver) <br>
[Maglev: A Fast and Reliable Software Network Load Balancer](https://research.google.com/pubs/pub44824.html) <br>
[MaxMind GeoIP databases](https://dev.maxmind.com/geoip/geoip2/downloadable/) <br>
[IPVS](http://www.linuxvirtualserver.org/software/ipvs.html) <br>
[Open vSwitch](http://www.openvswitch.org/) <br>
[kTLS in Linux (TLS in kernel space 4.13+)](https://github.com/ktls), [white paper](https://netdevconf.org/1.2/papers/ktls.pdf) and [Intro in Go](https://blog.filippo.io/playing-with-kernel-tls-in-linux-4-13-and-go/)<br>
[DPDK](http://dpdk.org/) <br>
[FD.io](https://fd.io/) <br>
[RIPE NCC network information](https://atlas.ripe.net/) <br>
[JLS2009: Generic receive offload](https://lwn.net/Articles/358910/) <br>
[High-Speed Trading: Lines, Radios, and Cables – Oh My](https://tabbforum.com/opinions/high-speed-trading-lines-radios-and-cables-oh-my) <br>
[Solving problem with Nagle's algorithm and delayed ACK using TCP\_NODELAY](http://www.stuartcheshire.org/papers/NagleDelayedAck/) <br>
[IPFS](https://ipfs.io/) <br>
[S/Kademlia: A Practicable Approach Towards Secure Key-Based Routing](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.68.4986) <br>
[Linux AnyIP](https://blog.widodh.nl/2016/04/anyip-bind-a-whole-subnet-to-your-linux-machine/) <br>
[Listen on all ports for AnyIP range on the server](https://blog.cloudflare.com/how-we-built-spectrum/) <br>
[TCP Tracepoints (Linux 4.15/6+)](http://www.brendangregg.com/blog/2018-03-22/tcp-tracepoints.html) <br>
[Kernel Connection Multiplexor (KCM)](https://lwn.net/Articles/657970/) and [more details](https://lwn.net/Articles/657999/) <br>
[Blocking-resistant communication through domain fronting](https://www.bamsoftware.com/papers/fronting/) <br>
[Anatomy of Linux DNS lookup](https://zwischenzugs.com/2018/06/08/anatomy-of-a-linux-dns-lookup-part-i/), [part 2](https://zwischenzugs.com/2018/06/18/anatomy-of-a-linux-dns-lookup-part-ii/), [part 3](https://zwischenzugs.com/2018/07/06/anatomy-of-a-linux-dns-lookup-part-iii/), [part 4](https://zwischenzugs.com/2018/08/06/anatomy-of-a-linux-dns-lookup-part-iv/), [part 5](https://zwischenzugs.com/2018/09/13/anatomy-of-a-linux-dns-lookup-part-v-two-debug-nightmares/) <br>
[Equal-cost multi-path routing (ECMP)](https://en.wikipedia.org/wiki/Equal-cost_multi-path_routing) <br>
[How LinkedIn used TCP Anycast to make the site faster](https://www.slideshare.net/shawnzandi/how-linkedin-used-tcp-anycast-to-make-the-site-faster) <br>
[Roughtime protocol](https://roughtime.googlesource.com/roughtime) <br>
[List of reserved IPv4 ranges (IANA IPv4 Special-Purpose Address Registry)](https://www.iana.org/assignments/iana-ipv4-special-registry/iana-ipv4-special-registry.xhtml)<br>
[List of reserved IPv6 ranges (IANA IPv6 Global Unicast Address Assignments)](https://www.iana.org/assignments/ipv6-unicast-address-assignments/ipv6-unicast-address-assignments.xhtml)<br>
[Wikipedia on reserved IP addresses](https://en.wikipedia.org/wiki/Reserved_IP_addresses)<br>
[TCP window scaling, timestamps and SACK](https://fedoramagazine.org/tcp-window-scaling-timestamps-and-sack/) <br>
[DNS SVCB and HTTPS records RFC (draft)](https://tools.ietf.org/html/draft-ietf-dnsop-svcb-https-01) <br>
[Networking ASICS overview in 2020](https://blog.cloudflare.com/asics-at-the-edge/) <br>
[How NAT traversal works](https://tailscale.com/blog/how-nat-traversal-works/) <br>
[Ethernet and IP Networking 101](https://iximiuz.com/en/posts/computer-networking-101/) <br>

# SDN

[Панельная дискуссия «SDN 10 лет после хайпа»](https://www.youtube.com/watch?v=a6F73J2qwqY) <br>
[Stratum](https://stratumproject.org/) <br>
[p4 language](https://p4.org/) <br>
[p4 Runtime](https://p4.org/p4-runtime/) <br>
[OpenFlow](https://www.opennetworking.org/software-defined-standards/specifications/) <br>
[SAI (Switch Abstraction Interface)](https://github.com/opencomputeproject/SAI) ⭐ 610 | 🐛 206 | 🌐 Python | 📅 2026-08-12 <br>
[ONOS](https://onosproject.org/) <br>
[OpenNFP](https://open-nfp.org/) <br>
[OpenConfig](http://openconfig.net/) <br>

# SRE (Site Reliability Engineering)

[Napking math numbers for estimating hardware and software performance](https://github.com/sirupsen/napkin-math) ⭐ 5,637 | 🐛 10 | 🌐 Rust | 📅 2026-03-21 <br>
[USENIX SREcon APAC 2022: Computing Performance: What's on the Horizon (Great overview by Brendan Gregg)](https://www.brendangregg.com/blog/2023-03-01/computer-performance-future-2022.html) <br>
[Google Site Reliability Engineering book](https://landing.google.com/sre/book.html) <br>
[Experience from running Uber payment service](https://blog.pragmaticengineer.com/operating-a-high-scale-distributed-system/) <br>
[Best practices of on-call (Increment journal issue)](https://increment.com/on-call/) <br>
[High Performance Browser Networking book](https://hpbn.co/) <br>
[The Docker Book](https://www.dockerbook.com/) <br>
[Site Reliability Engineer HandBook](https://s905060.gitbooks.io/site-reliability-engineer-handbook/) <br>
[Linux Performance tools and materials](http://www.brendangregg.com/linuxperf.html) <br>
[Understanding swap in Linux](https://chrisdown.name/2018/01/02/in-defence-of-swap.html) and [Video: Linux Memory Management at Scale: Under the Hood](https://www.youtube.com/watch?v=beefUhRH5lU) <br>
[How Much Memory Does the Process Really Take on Linux?](https://www.percona.com/blog/2020/09/11/how-much-memory-does-the-process-really-take-on-linux/) <br>
[U2F devices review](https://github.com/hillbrad/U2FReviews) ⭐ 431 | 🐛 9 | 📅 2018-09-06 <br>
[Optimizing web servers for high throughput and low latency (Dropbox)](https://blogs.dropbox.com/tech/2017/09/optimizing-web-servers-for-high-throughput-and-low-latency/) <br>
[Shipilev Close Encounters of The Java Memory Model Kind](https://shipilev.net/blog/2016/close-encounters-of-jmm-kind/) <br>
[On disk IO - part 1](https://medium.com/@ifesdjeen/on-disk-io-part-1-flavours-of-io-8e1ace1de017), [part 2](https://medium.com/@ifesdjeen/on-disk-io-part-2-more-flavours-of-io-c945db3edb13), [part 3](https://medium.com/@ifesdjeen/on-disk-io-part-3-lsm-trees-8b2da218496f), [part 4](https://medium.com/@ifesdjeen/on-disk-storage-part-4-b-trees-30791060741), [part 5](https://medium.com/@ifesdjeen/on-disk-io-access-patterns-in-lsm-trees-2ba8dffc05f9) <br>
[Transparent Hugepages: measuring the performance impact](https://alexandrnikitin.github.io/blog/transparent-hugepages-measuring-the-performance-impact/) <br>
[Introduction 2016 NUMA Deep Dive Series](http://frankdenneman.nl/2016/07/06/introduction-2016-numa-deep-dive-series/) <br>
[Understanding PCIe Configuration for Maximum Performance](https://community.mellanox.com/docs/DOC-2496) <br>
[Netflix Serving 100 Gbps from an Open Connect Appliance](https://medium.com/netflix-techblog/serving-100-gbps-from-an-open-connect-appliance-cdb51dda3b99) <br>
[Aphyr Hermitage - info and testing of database isolation levels](https://github.com/aphyr/hermitage) ⭐ 0 | 🐛 0 | 📅 2015-09-04 <br>
[A collection of postmortems](https://github.com/danluu/post-mortems) ⭐ 12,222 | 🐛 11 | 📅 2026-06-22 <br>
[Jeff Dean's latency numbers plotted over time](https://github.com/colin-scott/interactive_latencies) ⭐ 2,171 | 🐛 8 | 🌐 JavaScript | 📅 2024-08-11 <br>
[Sakila test DB](https://dev.mysql.com/doc/sakila/en/) <br>
[Monitoring in the time of Cloud Native](https://medium.com/@copyconstruct/monitoring-in-the-time-of-cloud-native-c87c7a5bfa3e) <br>
[Tyler McMullen - Load Balancing is Impossible](https://www.youtube.com/watch?v=kpvbOzHUakA) <br>
[What every programmer should know about memory](https://www.akkadia.org/drepper/cpumemory.pdf) <br>
[What every programmer should know about floating point](https://docs.oracle.com/cd/E19957-01/806-3568/ncg_goldberg.html), [floating points format explained](http://fabiensanglard.net/floating_point_visually_explained/), [Floating point GUI site](http://floating-point-gui.de/), [shorter explanation](http://blog.reverberate.org/2014/09/what-every-computer-programmer-should.html) <br>
[Chaos Engineering information map](https://coggle.it/diagram/5a229c7860c0c20001ae6caf/1960e86c369b09c4deac3227885bb073ae258e637b1b9e57be274125ac6e57b2) <br>
[A Gentle Introduction to Erasure Codes](https://www.akalin.com/intro-erasure-codes) <br>
[The PMCs of EC2: Measuring IPC](http://www.brendangregg.com/blog/2017-05-04/the-pmcs-of-ec2.html) <br>
[AWS EC2 Virtualization evolution](http://www.brendangregg.com/blog/2017-11-29/aws-ec2-virtualization-2017.html) <br>
[DNS zone visualization](http://dnsviz.net/) <br>
[How Netflix Tunes EC2](http://www.brendangregg.com/blog/2017-12-31/reinvent-netflix-ec2-tuning.html) <br>
[Write-Behind Logging](http://www.vldb.org/pvldb/vol10/p337-arulraj.pdf) <br>
[Cache-Oblivious Algorithms and Data Structures](http://erikdemaine.org/papers/BRICS2002/paper.pdf) <br>
[Oracle Graal (Hotspot replacement)](https://github.com/oracle/graal) ⭐ 21,662 | 🐛 843 | 🌐 Java | 📅 2026-08-14 <br>
[Understanding How Graal Works - a Java JIT Compiler Written in Java](http://chrisseaton.com/truffleruby/jokerconf17/) <br>
[Understanding disk usage in Linux](https://ownyourbits.com/2018/05/02/understanding-disk-usage-in-linux/) <br>
[On time and UTC](https://zachholman.com/talk/utc-is-enough-for-everyone-right) <br>
[The tail at scale (reducing latency long tail)](https://www2.cs.duke.edu/courses/cps296.4/fall13/838-CloudPapers/dean_longtail.pdf) <br>
[Optimizing ScyllaDB to run inside Docker container](https://www.scylladb.com/2018/08/09/cost-containerization-scylla/) <br>
[Using PMM with EverSQL to optimize queries](https://www.percona.com/blog/2019/01/22/monitor-and-optimize-slow-queries-with-pmm-and-eversql-part-one/) and [part 2](https://www.percona.com/blog/2019/01/28/monitor-and-optimize-slow-queries-with-pmm-and-eversql-part-2/) <br>
[Learn where some of the network sysctl variables fit into the Linux/Kernel network flow](https://github.com/leandromoreira/linux-network-performance-parameters) ⭐ 5,810 | 🐛 3 | 📅 2026-06-03 <br>
[Understanding CORS: Mozilla page](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS), [Stackoverflow on CORS](https://stackoverflow.com/questions/29954037/why-is-an-options-request-sent-and-can-i-disable-it) <br>
[A self-service CA for OpenSSH](https://github.com/nsheridan/cashier) ⭐ 729 | 🐛 39 | 🌐 Go | 📅 2025-10-29 <br>
[Shipilev JVM Anatomy Park](https://shipilev.net/jvm-anatomy-park/) <br>
[How does a relational database work](http://coding-geek.com/how-databases-work/) <br>
[Using systemd timers instead of cronjobs](https://opensource.com/article/20/7/systemd-timers) <br>
[Story of age, cache-control headers and prefetching mechanism in modern browsers](https://timkadlec.com/remembers/2020-06-17-prefetching-at-this-age/) <br>
[Is Your Linux Version Hiding Interrupt CPU Usage From You?](https://tanelpoder.com/posts/linux-hiding-interrupt-cpu-usage/) <br>
[HTTP Caching headers best practices](https://simonhearne.com/2022/caching-header-best-practices/) <br>

# Disk storage

[On Direct vs Buffered I/O and atomic writes](https://www.scylladb.com/2022/04/12/direct-i-o-writes-the-path-to-storage-wealth/), [SO on atomic writes from storage specification side](https://stackoverflow.com/questions/2009063/are-disk-sector-writes-atomic), [LWN on atomic writes](https://lwn.net/Articles/789600/) <br>
[Minio (local storage with AWS S3 API)](https://github.com/minio/minio) ⚠️ Archived <br>
[libzbc (direct disk access)](https://github.com/hgst/libzbc) ⭐ 165 | 🐛 0 | 🌐 C | 📅 2024-10-17 <br>
[SMR drives at Dropbox](https://blogs.dropbox.com/tech/2018/06/extending-magic-pocket-innovation-with-the-first-petabyte-scale-smr-drive-deployment/) <br>
[Intel VROC overview and performance testing](https://www.storagereview.com/intel_virtual_raid_on_cpu_vroc_review) <br>
[Blb (distributed object storage system developed by Upthere)](https://github.com/westerndigitalcorporation/blb) ⭐ 629 | 🐛 8 | 🌐 Go | 📅 2023-10-11 <br>
[Configuring OpenZFS to run 24x NVMe drives for high-load MySQL](https://github.com/letsencrypt/openzfs-nvme-databases) ⚠️ Archived <br>
[Achieving 11M IOPS & 66 GB/s IO on a Single ThreadRipper Workstation](https://tanelpoder.com/posts/11m-iops-with-10-ssds-on-amd-threadripper-pro-workstation/) and follow up [video](https://www.youtube.com/watch?v=5A531KE8O9Q)<br>

# TLS

[The Illustrated TLS Connection](https://tls.ulfheim.net/) <br>
[A Readable Specification of TLS 1.3](https://davidwong.fr/tls13/) <br>
[Sonar](https://sonarwhal.com/) <br>
[TLS information](https://istlsfastyet.com/) <br>
[Mutuals TLS (mTLS)](https://www.codeproject.com/Articles/326574/An-Introduction-to-Mutual-SSL-Authentication) <br>
[Mozilla server side TLS information](https://wiki.mozilla.org/Security/Server_Side_TLS) <br>
[BadTLS (SSL testing)](https://github.com/chromium/badssl.com) ⭐ 3,041 | 🐛 208 | 🌐 HTML | 📅 2026-06-01 <br>
[testssl.sh](https://github.com/drwetter/testssl.sh) ⭐ 9,165 | 🐛 250 | 🌐 Shell | 📅 2026-08-12 <br>
[Mozilla Observatory](https://observatory.mozilla.org/) <br>
[HTTP security headers testing](https://securityheaders.io/) <br>
[Qualys SSL tests](https://www.ssllabs.com/ssltest) <br>
[High-Tech Bridge SSL test](https://www.htbridge.com/ssl/) <br>
[HTTP security tools](https://report-uri.io/home/tools) <br>
[HSTS preloading](https://hstspreload.org) <br>
[SRI hash generator](https://www.srihash.org/) <br>
[Client side TLS test](https://www.howsmyssl.com/) <br>
[DNS CAA helper](https://sslmate.com/caa/) <br>
[DNS over TLS](https://tools.ietf.org/html/rfc7858) <br>
[Encrypted Client Hello (ECH) standard](https://datatracker.ietf.org/doc/html/draft-ietf-tls-esni-13), [ECH background](https://blog.cloudflare.com/handshake-encryption-endgame-an-ech-update/) <br>
[TLS Delegated Credentials](https://tools.ietf.org/html/draft-ietf-tls-subcerts-05) <br>
[Oblivious DNS over HTTPS RFC (draft)](https://tools.ietf.org/html/draft-pauly-dprive-oblivious-doh-03) <br>
[ECH (TLS Encrypted Client Hello) RFC](https://tools.ietf.org/html/draft-ietf-tls-esni), [Introduction to ECH](https://blog.cloudflare.com/encrypted-client-hello/) <br>

# HTTP/3 and QUIC

[HTTP/3 for everyone (video)](https://fosdem.org/2020/schedule/event/http3/) <br>
[HTTP/3 test site (Fastly)](https://http3.is/) <br>
[HTTP/3 Explained (book)](https://http3-explained.haxx.se/) <br>
[The Illustrated QUIC Connection](https://quic.xargs.org/) <br>
[msquic (QUIC protocol implementation from Microsoft)](https://github.com/microsoft/msquic) ⭐ 4,758 | 🐛 322 | 🌐 C | 📅 2026-08-14 <br>
[quiche (QUIC protocol implementation from Cloudflare)](https://github.com/cloudflare/quiche) ⭐ 11,767 | 🐛 299 | 🌐 Rust | 📅 2026-08-14 <br>

# Authorization and Authentication

OAuth 2.0 information: [Practical information](https://oauth.net/), [book](https://oauth2simplified.com/), [online version of the book](https://www.oauth.com/), [best practices (RFC)](https://tools.ietf.org/html/draft-ietf-oauth-security-topics-14), [browser-bases apps guideline (RFC)](https://tools.ietf.org/html/draft-ietf-oauth-browser-based-apps-04), [RFC](https://tools.ietf.org/html/rfc6749) <br>
[AppAuth (OAuth 2.0 client library)](https://appauth.io/) <br>
[JSON Web Token (JWT)](https://tools.ietf.org/html/rfc7519) <br>
[JSON Web Signature (JWS)](https://tools.ietf.org/html/rfc7515) <br>
[JSON Web Encryption (JWE)](https://tools.ietf.org/html/rfc7516) <br>
[JWT playground](https://jwt.io/) <br>
[CBOR Web Token (CWT)](https://datatracker.ietf.org/doc/html/rfc8392) <br>
[CBOR information](https://cbor.io/) <br>
[CBOR playground](http://cbor.me/) <br>

# Cryptography

[OpenSSL](https://www.openssl.org/) <br>
[BoringSSL (Google)](https://boringssl.googlesource.com/boringssl/) <br>
[s2n (AWS)](https://github.com/awslabs/s2n) ⭐ 4,750 | 🐛 305 | 🌐 C | 📅 2026-08-14 <br>
[LibreSSL (OpenBSD OpenSSL fork)](https://github.com/libressl-portable/portable) ⭐ 1,487 | 🐛 102 | 🌐 C | 📅 2026-08-14 <br>
[Google Tink](https://github.com/google/tink) ⚠️ Archived <br>
[Thesis (encryption framework)](https://github.com/cossacklabs/themis) ⭐ 1,971 | 🐛 31 | 🌐 C | 📅 2026-04-24 <br>
[Acra (DB encryption proxy)](https://github.com/cossacklabs/acra) ⭐ 1,491 | 🐛 21 | 🌐 Go | 📅 2026-04-23 <br>
[Ascon (2023 winner of lightweight cryptography)](https://ascon.iaik.tugraz.at/) <br>
[Lightweight cryptography algorithms (NIST)](https://csrc.nist.gov/projects/lightweight-cryptography) <br>
[Cryptography Engineering: Design Principles and Practical Applications (book)](https://www.amazon.com/Cryptography-Engineering-Principles-Practical-Applications/dp/0470474246) <br>
[Introduction to Modern Cryptography, Second Edition (book)](https://www.amazon.com/Introduction-Cryptography-Chapman-Network-Security/dp/1466570261) <br>
[Security Engineering, 2nd edition (book)](https://www.amazon.com/Security-Engineering-Building-Dependable-Distributed/dp/0470068523) <br>
[Crypto 101 (concepts, book)](https://www.crypto101.io/) <br>
[Applied Cryptography Engineering](https://sockpuppet.org/blog/2013/07/22/applied-practical-cryptography/) <br>
[Ensuring Randomness with Linux's Random Number Generator](https://blog.cloudflare.com/ensuring-randomness-with-linuxs-random-number-generator/) <br>
[Should we MAC-then-encrypt or encrypt-then-MAC?](https://crypto.stackexchange.com/questions/202/should-we-mac-then-encrypt-or-encrypt-then-mac) <br>
[Authenticated Encryption: Relations among notions and analysis of the generic composition paradigm](https://eprint.iacr.org/2000/025) <br>
[How to choose an Authenticated Encryption mode](https://blog.cryptographyengineering.com/2012/05/19/how-to-choose-authenticated-encryption/) <br>
[Awesome cryptography repository](https://github.com/sobolevn/awesome-cryptography) ⭐ 7,067 | 🐛 71 | 📅 2026-07-15 <br>
[Mind Your Keys? A Security Evaluation of Java Keystores](https://www.ndss-symposium.org/wp-content/uploads/2018/02/ndss2018_02B-1_Focardi_paper.pdf) <br>
[Hash-based message authentication code](https://en.wikipedia.org/wiki/Hash-based_message_authentication_code) <br>
[Authenticated Encryption with Associated Data (AEAD)](https://en.wikipedia.org/wiki/Authenticated_encryption) <br>
[AES-GCM (AEAD)](https://tools.ietf.org/html/rfc5288) <br>
[AES-GCM-SIV](https://github.com/Shay-Gueron/AES-GCM-SIV) ⭐ 121 | 🐛 2 | 🌐 C | 📅 2019-07-01 <br>
[GCM blockcipher mode](https://en.wikipedia.org/wiki/Galois/Counter_Mode) <br>
[OCB blockcipher mode](http://web.cs.ucdavis.edu/~rogaway/ocb/) <br>
[ChaCha20 design (stream)](http://loup-vaillant.fr/tutorials/chacha20-design) <br>
[Poly1305 (MAC)](https://cr.yp.to/mac.html) <br>
[ChaCha20 and Poly1305 (AEAD)](https://www.rfc-editor.org/rfc/rfc8439) <br>
[AEGIS-128X (fast authentication cipher with AVX/AES acceleration)](https://github.com/jedisct1/aegis-128X) ⭐ 39 | 🐛 0 | 🌐 Zig | 📅 2024-12-18 <br>
[Understanding RSA terms](https://security.stackexchange.com/questions/68822/trying-to-understand-rsa-and-its-terminology/68836#68836) <br>
[Elliptic curve introduction](https://www.imperialviolet.org/2010/12/04/ecc.html) <br>
[Elliptic Curve Cryptography: a gentle introduction](http://andrea.corbellini.name/2015/05/17/elliptic-curve-cryptography-a-gentle-introduction/) <br>
[Safe elliptic curvers](https://safecurves.cr.yp.to/) <br>
[Curve25519](https://cr.yp.to/ecdh/curve25519-20060209.pdf) <br>
[Hybrid Public Key Encryption (HPKE) RFC](https://datatracker.ietf.org/doc/html/rfc9180), [Example of HPKE usage in Cloudflare](https://blog.cloudflare.com/using-hpke-to-encrypt-request-payloads/) <br>
[Fully Homomorphic Encryption library (Google, C++)](https://github.com/google/fully-homomorphic-encryption) ⭐ 3,654 | 🐛 1 | 🌐 Starlark | 📅 2026-08-14 <br>
[Understanding HKDF](https://soatok.blog/2021/11/17/understanding-hkdf/) <br>
[Database Cryptography Fur the Rest of Us](https://soatok.blog/2023/03/01/database-cryptography-fur-the-rest-of-us/) <br>
[Intro to Linux Kernel Key Retention Service](https://blog.cloudflare.com/the-linux-kernel-key-retention-service-and-why-you-should-use-it-in-your-next-application/) <br>

# Hashing

[smhasher testing suite](https://github.com/rurban/smhasher) ⭐ 2,170 | 🐛 46 | 🌐 C++ | 📅 2026-07-04 <br>
[Article "Programmers Don’t Understand Hash Functions"](https://soatok.blog/2021/08/24/programmers-dont-understand-hash-functions/) <br>
[Fast Positive Hash](https://github.com/leo-yuriev/t1ha) ⚠️ Archived <br>
[Meow hash](https://github.com/cmuratori/meow_hash) ⭐ 1,829 | 🐛 22 | 🌐 C++ | 📅 2022-07-31 <br>
[HighwayHash and SipHash (Google)](https://github.com/google/highwayhash/) ⚠️ Archived <br>
[SipHash (original)](https://131002.net/siphash/) <br>
[BLAKE3 (crypto)](https://github.com/BLAKE3-team/BLAKE3) ⭐ 6,372 | 🐛 195 | 🌐 Assembly | 📅 2026-08-05 <br>
[BLAKE2 (crypto)](https://blake2.net/) <br>
[xxHash](http://www.xxhash.com/) <br>
[MurmurHash3](https://github.com/aappleby/smhasher) ⭐ 2,886 | 🐛 69 | 🌐 C++ | 📅 2026-06-25 <br>
[argon2 (password hashing)](https://github.com/P-H-C/phc-winner-argon2) ⭐ 5,351 | 🐛 102 | 🌐 C | 📅 2024-08-06 <br>
[Dieharder: A Random Number Test Suite](http://webhome.phy.duke.edu/~rgb/General/dieharder.php) <br>
[yescrypt (KDF and password hashing)](https://www.openwall.com/yescrypt/) <br>
["How to Encipher Messages on a Small Domain. Deterministic Encryption and the Thorp Shuffle" (encryption hashing whitepaper)](https://www.cs.ucdavis.edu/~rogaway/papers/thorp.pdf) <br>

# UUID

[UUID version 6/7/8 RFC draft](https://datatracker.ietf.org/doc/draft-peabody-dispatch-new-uuid-format/) <br>
[UUID version 6/7/8 RFC work in progress](https://github.com/uuid6/uuid6-ietf-draft) ⚠️ Archived <br>
[UUID version 7 playground](http://www.new-uuid.info/) <br>
[TypeID (type-safe extension of UUIDv7)](https://github.com/jetpack-io/typeid) ⭐ 3,630 | 🐛 10 | 🌐 Go | 📅 2026-07-17 <br>
[Why UUIDv7? (RU)](https://habr.com/ru/post/572700/) <br>
[KSUID](https://github.com/segmentio/ksuid) ⭐ 5,262 | 🐛 22 | 🌐 Go | 📅 2026-06-25 <br>

# Real User Monitoring

[boomerang library](https://github.com/akamai/boomerang) ⭐ 1,922 | 🐛 15 | 🌐 JavaScript | 📅 2026-07-10 and [How to use boomerang](https://developer.akamai.com/tools/boomerang/) <br>
Custome backend required for boomerang - could use [boomcatch](https://github.com/springernature/boomcatch) ⭐ 111 | 🐛 26 | 🌐 JavaScript | 📅 2026-03-10 and [statsd](https://github.com/statsd/statsd) ⭐ 18,069 | 🐛 90 | 🌐 JavaScript | 📅 2025-05-20 <br>
Commercial solution is [Akamai mPulse](https://www.akamai.com/us/en/products/performance/mpulse-real-user-monitoring.jsp) <br>
[sitespeed.io tools](https://github.com/sitespeedio) <br>
[Matomo](https://matomo.org/) <br>
User access information from logs: [GoAccess](https://goaccess.io/) and [AWStats](https://github.com/eldy/awstats) ⭐ 434 | 🐛 136 | 🌐 Perl | 📅 2025-11-10 <br>
[Compress data from ResourceTiming API](https://github.com/nicjansma/resourcetiming-compression.js) ⭐ 60 | 🐛 2 | 🌐 JavaScript | 📅 2024-10-11 <br>
[Javascript Performance APIs](https://developer.mozilla.org/en-US/docs/Web/API/Performance) <br>
[Javascript Navigation Timing API](https://developer.mozilla.org/en-US/docs/Web/API/Navigation_timing_API) <br>

# QA Automation

[Learn headless browser automation](https://theheadless.dev/) <br>
[Playwright](https://playwright.dev/) <br>
[QA Wolf (Playwright scripts generation)](https://github.com/qawolf/qawolf) ⭐ 3,441 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-14 <br>
[Headless Recorder (Playwright/Puppeteer scripts generation)](https://github.com/checkly/headless-recorder) ⚠️ Archived <br>
[Puppeteer](https://pptr.dev/) <br>
[Selenium](https://www.selenium.dev/) <br>
[Cypress](https://www.cypress.io/) <br>
[mimesis (fake data generator)](https://github.com/lk-geimfari/mimesis) ⭐ 4,840 | 🐛 12 | 🌐 Python | 📅 2026-08-05 <br>

# Tools

[htop](https://github.com/hishamhm/htop) ⚠️ Archived <br>
[gtop](https://github.com/aksakalli/gtop) ⭐ 9,925 | 🐛 42 | 🌐 JavaScript | 📅 2025-11-06 <br>
[nvtop](https://github.com/Syllo/nvtop) ⭐ 10,916 | 🐛 142 | 🌐 C | 📅 2026-05-06 <br>
[k6 (load testing)](https://k6.io/) <br>
[dnstrace](https://github.com/rs/dnstrace) ⭐ 285 | 🐛 7 | 🌐 Go | 📅 2022-12-10 <br>
[upx](https://upx.github.io/) <br>
[bat](https://github.com/sharkdp/bat) ⭐ 60,181 | 🐛 420 | 🌐 Rust | 📅 2026-08-11 <br>
[httpie](https://github.com/jakubroztocil/httpie) ⭐ 38,419 | 🐛 330 | 🌐 Python | 📅 2024-12-17 <br>
[smenu](https://github.com/p-gen/smenu) ⭐ 2,491 | 🐛 4 | 🌐 C | 📅 2026-04-17 <br>
[awesome tmux](https://github.com/rothgar/awesome-tmux) ⭐ 10,241 | 🐛 5 | 📅 2026-08-07 <br>
[py-spy (python profiler)](https://github.com/benfred/py-spy) ⭐ 15,434 | 🐛 236 | 🌐 Rust | 📅 2026-08-14 <br>
[kubespy](https://github.com/pulumi/kubespy) ⭐ 3,078 | 🐛 18 | 🌐 Go | 📅 2026-08-14 <br>
[up](https://github.com/akavel/up) ⭐ 8,838 | 🐛 30 | 🌐 Go | 📅 2024-09-05 <br>
[doh](https://github.com/picatz/doh) ⭐ 120 | 🐛 4 | 🌐 Go | 📅 2026-07-03 <br>
[fx](https://github.com/antonmedv/fx) ⭐ 20,579 | 🐛 24 | 🌐 Go | 📅 2026-07-28 <br>
[jid](https://github.com/simeji/jid) ⭐ 7,132 | 🐛 10 | 🌐 Go | 📅 2026-08-02 <br>
[dive](https://github.com/wagoodman/dive) ⭐ 54,454 | 🐛 209 | 🌐 Go | 📅 2025-12-15 <br>
[nnn](https://github.com/jarun/nnn) ⭐ 21,788 | 🐛 4 | 🌐 C | 📅 2026-08-15 <br>
[ethr](https://github.com/Microsoft/Ethr) ⭐ 5,865 | 🐛 51 | 🌐 Go | 📅 2026-07-03 <br>
[termshark (CLI UI for Wireshark)](https://github.com/gcla/termshark) ⭐ 9,957 | 🐛 50 | 🌐 Go | 📅 2024-04-30 <br>
[xdpcap (tcpdump for XDP)](https://github.com/cloudflare/xdpcap) ⭐ 782 | 🐛 16 | 🌐 Go | 📅 2026-07-30 <br>
[flan (nmap based vulnerability scanner)](https://github.com/cloudflare/flan) ⚠️ Archived <br>
[broot (files)](https://github.com/Canop/broot) ⭐ 12,891 | 🐛 248 | 🌐 Rust | 📅 2026-08-13 <br>
[bandwidth](https://github.com/imsnif/bandwhich) ⭐ 11,897 | 🐛 54 | 🌐 Rust | 📅 2026-08-01 <br>
[sandmap](https://github.com/trimstray/sandmap) ⭐ 1,861 | 🐛 13 | 🌐 Shell | 📅 2024-11-19 <br>
[duf (advanced du)](https://github.com/muesli/duf) ⭐ 15,263 | 🐛 81 | 🌐 Go | 📅 2026-01-13 <br>

# Misc

[High Scalability/Availability/Stability articles list](https://github.com/binhnguyennus/awesome-scalability) ⭐ 73,293 | 🐛 26 | 📅 2026-01-04 <br>
[Another github repo](https://github.com/rShetty/awesome-distributed-systems) ⭐ 1,628 | 🐛 2 | 📅 2025-07-23 <br>

# Videos

[Kafka 2017 Summit](https://www.confluent.io/kafka-summit-sf17/resource/) <br>
[CppCon 2017](https://www.youtube.com/playlist?list=PLHTh1InhhwT6bwIpRk0ZbCA0N2p1taxd6) <br>
[@Scale 2017](https://atscaleconference.com/videos-articles/) <br>
[Strange Loop 2017](https://www.youtube.com/channel/UC_QIfHvN9auy2CoOdSfMWDw) <br>
[FOSDEM 2018](https://www.youtube.com/user/fosdemtalks/videos) <br>
[Computer Architecture course taught at ETH Zürich in Fall 2017](https://www.youtube.com/playlist?list=PL5Q2soXY2Zi9OhoVQBXYFIZywZXCPl4M_) <br>
[GrafanaCon 2018](https://www.youtube.com/playlist?list=PLDGkOdUX1UjpXR6BexaDoOIc0ksE2MzFI) <br>
[SREcon 2018](https://www.youtube.com/playlist?list=PLbRoZ5Rrl5lcszsvhnb4P9Ds4pSmVtkfp) <br>
[KubeCon + CloudNativeCon 2018](https://www.youtube.com/playlist?list=PLj6h78yzYM2N8GdbjmhVU65KYm_68qBmo) <br>
[Networking @Scale 2018](https://code.fb.com/core-data/networking-scale-2018-recap/) <br>
[Highload++ Siberia 2018](http://www.highload.ru/siberia/2018/) <br>
[GrafanaCon 2019](https://www.youtube.com/playlist?list=PLDGkOdUX1UjqKc3ryyoSpWZvs7yktklQr) <br>
[SREcon 2020 Americas](https://www.youtube.com/playlist?list=PLbRoZ5Rrl5lfLXUjFjS0mP1XzNzNZMhYN) <br>
[FAST '21](https://www.youtube.com/watch?v=yjme8LOyhfY\&list=PLbRoZ5Rrl5lckayzBszGg_Pq6O1nq5EdV) <br>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
