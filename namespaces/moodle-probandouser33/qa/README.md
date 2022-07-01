flux create kustomization moodle-probandouser33-qa
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
