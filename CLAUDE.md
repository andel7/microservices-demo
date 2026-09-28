# Online Boutique (TeraSky fork)
11 gRPC services in src/<service>/, one Deployment each in kubernetes-manifests/<service>.yaml, shared proto in protos/demo.proto.
Build from src/<service>/Dockerfile, push to the service's ECR repo, deploy with kubectl apply -f kubernetes-manifests/<service>.yaml.
Owners, environments, ECR repos, API consumers and platform docs live in Backstage — use the MCP.
Only what's in the repo runs in the cluster.
