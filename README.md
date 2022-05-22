# k8s-helm-learning
Random test projects to learn K8s and Helm


kubectl exec -it postgres-7b9fb8d6c5-q4w7s -- psql -U admin --password -h localhost -p 5432 postgresdb


to initialize charts: helm install [chart-name] [chart-location]

helm upgrade charts with changes: helm upgrade [chart-name] [chart-location]
