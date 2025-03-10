## Container orchestration, Kubernetes basics, part 7, 01 Nov 2022

### Prerequisites ###

- The following commands were executed on VM with [Manjaro Linux distribution](https://manjaro.org/download/) (however, they might be performed on another Linux distribution, but the command might differ, e.g. another package manager etc.)
- Docker installed (see [Lesson 5 prerequisites](../05_docker_basic_commands_postgres_23-aug-2022/README.md))
- Make sure that the steps of common [Prerequisites](https://github.com/Alliedium/springboot-api-rest-example/tree/master/.k8s#prerequisites) are completed.
- As for Example 10 [Prerequisites](https://github.com/Alliedium/springboot-api-rest-example/tree/master/.k8s/10-zalando-postgres-ha-operator#prerequisites) and [Step 1](https://github.com/Alliedium/springboot-api-rest-example/tree/master/.k8s/10-zalando-postgres-ha-operator#1-install-postgres-operator-via-helm-chart)
from `.k8s` folder of the project have to be completed.

### Steps ###

Follow the steps of [Alliedium/springboot-api-rest-example](https://github.com/Alliedium/springboot-api-rest-example/). 

### References ###

1. [Kubernetes explained in pictures: the theme park analogy](https://danlebrero.com/2018/07/09/kubernetes-explained-in-pictures-the-theme-park-analogy/)
2. [Kubernetes services, pods, ingress ... all the basic components](https://www.padok.fr/en/blog/kubernetes-essentials-components-pods-services)
3. [Kubernetes Deployments vs StatefulSets](https://stackoverflow.com/questions/41583672/kubernetes-deployments-vs-statefulsets#:~:text=Deployment%20is%20a%20resource%20to,be%20using%20its%20own%20Volume)
4. [Kubernetes Components](https://kubernetes.io/docs/concepts/overview/components/)
5. [Kubernetes Components (rus)](https://kubernetes.io/ru/docs/concepts/overview/components/)
6. [K3S + K3D = K8S : a new perfect match for dev and test](https://www.sokube.ch/post/k3s-k3d-k8s-a-new-perfect-match-for-dev-and-test)
7. [Kubernetes | Custom Resources](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/)
8. [Kubernetes | Operator pattern](https://kubernetes.io/docs/concepts/extend-kubernetes/operator/)
9. [Kubernetes API](https://kubernetes.io/docs/reference/kubernetes-api/)
10. [CRD is just a table in Kubernetes](https://itnext.io/crd-is-just-a-table-in-kubernetes-13e15367bbe4)
11. [Kubernetes CustomResourceDefinitions (CRDs) | Tutorial](https://www.containiq.com/post/kubernetes-crds-custom-resource-definitions)
12. [Understanding High Availability
    options for PostgreSQL](https://postgresconf.org/system/events/document/000/000/801/PostgreSQL_Conference.pdf)
13. [What’s the Best PostgreSQL High Availability Framework? PAF vs. repmgr vs. Patroni Infographic](https://medium.com/@kristi.anderson/whats-the-best-postgresql-high-availability-framework-paf-vs-repmgr-vs-patroni-infographic-8f11f3972ef3)
14. [PostgreSQL Automatic Failover (PAF)](https://github.com/ClusterLabs/PAF)
15. [PostgreSQL HA packaged by Bitnami (repmgr)](https://github.com/bitnami/charts/tree/master/bitnami/postgresql-ha/)
16. [Postgres Operator by Zalando](https://github.com/zalando/postgres-operator)
17. [Postgres Operator by Zalando | Deployment options](https://github.com/zalando/postgres-operator/blob/master/docs/quickstart.md#deployment-options)
18. [Postgres Operator by Zalando | Deployment options | Helm chart (github)](https://github.com/zalando/postgres-operator/blob/master/docs/quickstart.md#helm-chart)
19. [Postgres Operator by Zalando | Deployment options | Helm chart (readthedocs)](https://postgres-operator.readthedocs.io/en/latest/quickstart/#helm-chart)