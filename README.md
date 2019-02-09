# Hyper blog

Purposely over-engineered infrastructure powering my personal blog

## Kubernetes cluster

There's a Kubernetes cluster running on Google Kubernetes Engine (GKE) in Google Cloud Platform (GCP).

The `tijmen-website` cluster has 3 `f1-micro` nodes (the smallest on Google Cloud Platform). It's in `europe-west1-b`.

It's using the `Cloud Source Repositories API` and `Cloud Build API`.
