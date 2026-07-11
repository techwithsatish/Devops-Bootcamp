# Today i have writen some kubernatives config files using the minikube

```
Deployment
│
├── apiVersion
├── kind
├── metadata
│   ├── name
│   └── labels
│
└── spec
    ├── replicas
    ├── selector
    │   └── matchLabels
    │
    └── template
        ├── metadata
        │   └── labels
        │
        └── spec
            └── containers
                ├── name
                ├── image
                ├── ports
                └── env
                    ├── MONGO_INITDB_ROOT_USERNAME
                    └── MONGO_INITDB_ROOT_PASSWORD

```
