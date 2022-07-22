flux create kustomization moodle-probando67-prod
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
