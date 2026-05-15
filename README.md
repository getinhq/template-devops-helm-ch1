# Helm chart upgrade lab

## Task
Deploy an Nginx chart with Helm and perform a rolling upgrade to a newer image tag.

## Starter (not finished)
Chart skeleton is provided. Set `image.tag` in `values.yaml`, run `helm upgrade`, and document steps here.

## Your work
1. `helm lint chart`
2. `helm install devops-nginx ./chart` (or upgrade)
3. Change `values.yaml` tag, run `helm upgrade` and verify rollout
