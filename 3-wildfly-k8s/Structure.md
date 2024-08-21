wildfly-k8s/
├── base/
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── configmap.yaml
│   ├── servicemonitor.yaml
│   └── kustomization.yaml
└── overlays/
    └── staging/
        ├── kustomization.yaml
        └── replica-count.yaml