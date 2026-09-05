# Third-party notices

The Compose files refer to external software and services. The references are
not copies of those projects and this repository does not relicense them:

- nginx and the nginx:latest image.
- GitLab Enterprise Edition and the gitlab/gitlab-ee:latest image.
- Confluent Platform images, including confluentinc/cp-zookeeper,
  confluentinc/cp-kafka, and confluentinc/cp-enterprise-control-center.
- Bitnami ZooKeeper and Kafka images.
- acme.sh, retrieved by the example command from its upstream distribution.
- Docker Compose and the host Docker runtime.

Image names, service names, URLs, and package references are used only to
describe dependencies. Their code, image layers, documentation, trademarks,
and license terms are outside the scoped MIT grant. The `.env` files and
user-provided values are also excluded.

[LICENSES/MIT.txt](LICENSES/MIT.txt) applies only to the exact first-party
paths listed in LICENSE-SCOPE.md; it is not a license for any third-party
dependency or unlisted file.
