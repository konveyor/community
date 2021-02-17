Move2Kube Validate:
-------------------

Move2Kube has `move2kube validate` command which allows for aggregated display of TODO actions after Move2Kube artifacts are generated. Currently this action lists only `TODO` actions that are part of the annotations in generated yamls. 

The scope of this idea will be to enhance the framework to support more action types like `FIX`, `VALIDATE`, etc. Also this framework needs to be extended to support other types of artifacts such as Dockerfile, containerization scripts, etc.

The activity will invoke,

1. Understanding Move2Kube workflow.
1. Understanding and coming up with a refined proposal for a updated validation framework.
1. Implementing the validation framework
1. Writing tests and documenting the framweork.