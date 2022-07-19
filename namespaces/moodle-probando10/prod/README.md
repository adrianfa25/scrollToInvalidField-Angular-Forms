flux create kustomization moodle-probando10-prod
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
