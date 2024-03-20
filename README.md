# CML MLOps Banking MLFlow

This is a lab with workspace to workspace model transfer via MLFlow Registry in CML.

### MLFlow in CML

CML supports MLFlow Tracking and Registry. With the former you can track your experiments from interactive notebook sessions. With the latter you can move experiment runs along with dependencies into a central repository shared by multiple CML Workspaces.  

The Registry is a fundamental component in the Enterprise MLOps architecture with CML. Among its advantages, it packages model experiments in a uniform format to accellerate collaboration, deployments, and model reproducibility.

Furthermore, it provides a central UI for tracking important model information such as model creator, time of creation, version, and other metadata.
Finally, when multiple workspaces are deployed, it acts as a security layer to provide a subset of users with the tooling to move a model from a DEV to a PRD environment.

In this lab you will use MLFlow for all the above. First you will act as a developer and create a model experiment in a DEV workspace; then you will act as a ML engineer and take that model concept into the PRD workspace.

### Use Case

You will explore data at scale with PySpark and develop an XGBoost classifier to predict fraudulent credit card transactions. 
