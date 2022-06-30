flux create kustomization moodle-probandoqa
		--source=flux-system
		--path="./st-eks-003"
		--prune=true
		--interval=10m
