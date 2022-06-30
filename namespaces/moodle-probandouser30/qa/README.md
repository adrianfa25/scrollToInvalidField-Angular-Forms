flux create kustomization moodle-probandouser30-qa
  --source=flux-system
  --path="./st-eks-003"
  --prune=true
  --interval=10m
