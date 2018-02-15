A handy lookup table of similar technology and services to help xooglers survive the *real* world :)  
pull-requests welcomed. this doc is only intended for well-known technology and services.

See also: [The Hadoop Ecosystem Table](https://hadoopecosystemtable.github.io/)

__Please do not list any confidential projects!__

## Technology

### Core Technology

| Google Internal   | Google Open Source   |  Open Source  |
| -------------     |  -------------       |-------------  |
| MapReduce         |     | Apache Hadoop, Spark  |
| Protocol Buffer   | [Protobuf](https://github.com/google/protobuf)    | Avro, Thrift      |
| network protocol | gRPC | bolt, thrift |
| Chubby            |      | Apache Zookeeper      |
| ? | | apache kafka, apache pulsar |


### Infrastructure

| Google Internal   | Google Open Source   |  Open Source  |
| -------------     |  -------------       |-------------  |
| Borg              |                      | Apache Mesos, Kubernetes  |
| GSLB (load balancer)| | ELB, [Istio](https://istio.io/), [F5](https://f5.com/products/big-ip), [envoy](https://github.com/lyft/envoy) |


### Storage

| Google Internal  | Google Open Source | Open Source    |
| -------------|------------ |-------------|
| GFS/Colossus| | HDFS, [Ceph](https://ceph.com), [GlusterFS](https://www.gluster.org) |
| BigTable     |   | Cassandra, HBase, accumulo, dynamoDB |
| [Spanner](http://research.google.com/archive/spanner.html)   | [cloud spanner](https://cloud.google.com/spanner/) | [CockroachDB](https://github.com/cockroachdb/cockroach) | 
| columnIO | | Apache Parquet |
| sstable | levelDB | |


### Services

| Google Internal  | Google Open Source | Open Source    |
| -------------|------------ |-------------|
| Dremel       |             | Apache Drill, [Presto](https://prestodb.io), AWS Athena, Spark(sort-of) |
| Dremel UI    |             | https://redash.io/ |
| Search (Mustang, Alexandria) |             | Lucene, Solr, Elasticsearch |
| pubsub | [pubsub](https://cloud.google.com/pubsub/docs/overview) | rabbitMQ, aws sns/sqs |

### DevOps
| Google Internal  | Google Open Source | Real World    |
| -------------|------------ |-------------|
| Blaze        |  [Bazel] (http://bazel.io)          |  |
| Oncall       |             | [PagerDuty](https://pagerduty.com), [OpsGenie](https://www.opsgenie.com/), [VictorOps](https://victorops.com/) |
| varz/borgmon | | [Prometheus](https://prometheus.io), [librato](https://www.librato.com), [newrelic](http://newrelic.com), skylight, scout, also [this](https://vimeo.com/173610242) and [this](https://prometheus.io/docs/introduction/comparison/) |
| Exception/Error Tracking (??) | | Sentry.io, Raygun.io, Rollbar, Honeybadger, Airbrake, OverOps |
| styleguides | [google styleguides](https://github.com/google/styleguide) | |
| blaze test / build / CI | | buildkite, circleCI, travis, jenkins, gitlabCI |
| continuous delivery / releasing | | [lambdaCD](http://www.lambda.cd), screwdriver.cd, [CodeShip](https://codeship.com), [shipit-engine](https://github.com/Shopify/shipit-engine), [GoCD](https://www.gocd.org), [AWS CodeDeploy](https://aws.amazon.com/codedeploy/), [Capistrano](https://www.capistranorb.com), [Fabric](https://www.fabfile.org), [ConcourseCI](https://concourse.ci/)|
| borg / borgcfg || [AWS Cloudformation](https://aws.amazon.com/cloudformation/), Puppet, Chef, Salt, Ansible, [Terraform](https://www.terraform.io) |
| logging || logstash, fluentd, papertrail, [cernan](https://github.com/postmates/cernan) |

## Operational
| Google Internal  |   Real World  |
| -------------    | ------------- |
| free food        |   :(          |
| [software engineering at google](https://arxiv.org/ftp/arxiv/papers/1702/1702.01715.pdf) | |
| valentine        | [1Password](https://support.1password.com/create-share-vaults/)  |
| OWNERS files in repo     | [github CODEOWNERS](https://github.com/blog/2392-introducing-code-owners) |
| snippets         | https://github.com/Khan/snippets |
