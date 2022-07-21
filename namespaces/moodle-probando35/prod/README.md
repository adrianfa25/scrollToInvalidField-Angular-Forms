flux create kustomization moodle-probando35-prod
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
