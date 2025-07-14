1. Refactor your repo to be such as:

    - app/demo/base/...
    - app/demo/overlays/dev/... (have a configmap change)
    - app/demo/overlays/prod/.. (have a configmap change and image change)

    - Each project (dev, prod) should be a different namespace

2. Create applicationset.yaml to mannually k apply -f .

    applicationset creates applications 
