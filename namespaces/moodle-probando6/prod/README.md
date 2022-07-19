flux create kustomization moodle-probando6-prod
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
