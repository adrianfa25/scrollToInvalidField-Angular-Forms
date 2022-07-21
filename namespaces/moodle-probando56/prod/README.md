flux create kustomization moodle-probando56-prod
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
