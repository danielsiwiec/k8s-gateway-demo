# Kubernetes Gateway API demo

Companion repo to the post on https://danoncoding.com on Kubernetes Gateway API.

## Contents
`/gateway` - Kubernetes Gateway API implementation

`/ingress` - Ingress implementation

## Prerequisites
- K8s cluster
- Helm v3

## Running the code

1. `helm upgrade --install gateway-demo gateway`
2. Open http://localhost and see the nginx landing page
3. `helm delete gateway-demo`
4. `helm upgrade --install ingress-demo ingress`
5. Open http://localhost and see the nginx landing page
6. `helm delete ingress-demo` 