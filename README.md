AIMS/
 ├── README.md
 ├── docs/              # Diagrams, flowcharts, compliance docs
 ├── core-services/
 │   ├── store-node/     # Store module (POS + local sync)
 │   ├── warehouse-node/ # Warehouse/DC module (pick/pack + sync)
 │   ├── logistics-node/ # Logistics/fleet node (dispatch + sync)
 │   ├── sync-engine/    # Universal offline/online sync logic
 │   ├── api-gateway/    # REST/GraphQL gateway for all modules
 │   └── auth-service/   # User/role auth, encryption, audit trails
 ├── common-libs/       # Shared utils: logging, config, encryption
 ├── infra/             # Docker, k8s deploy files, Terraform for cloud infra
 ├── tests/             # Unit + integration tests for every module
 ├── ci-cd/             # GitHub Actions pipelines for auto-build + deploy
 └── examples/          # Sample configs, local dev scripts