flux create kustomization moodle-asdas-qa
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
