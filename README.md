# flux-testing
Repository for configuration for flux-testing on river-dev 

The configurations here control a servicex instance in the sthapa namespace on
river-dev.  Check-ins are tested to ensure that the kustomize config doesn't
break.  Note that all services need to exist within the sthapa namespace and
flux/k8s will reject changes.  

