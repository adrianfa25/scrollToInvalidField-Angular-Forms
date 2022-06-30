flux create kustomization moodle-probandouser14--prod
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
