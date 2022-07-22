flux create kustomization moodle-probando74-prod
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
