flux create kustomization moodle-probandouser35-qa
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
