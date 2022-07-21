flux create kustomization moodle-probando42-prod
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
