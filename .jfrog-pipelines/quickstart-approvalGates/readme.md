Approval Gates enables you to insert a manual approval process for a step in your pipeline. When enabled, the step (and the pipeline run) goes into Pending Approval status when upstream steps finish and the run execution reaches that step. The following can be defined as part of this approval process:

* **List of approvers**: List of users who can approve or reject the step.
* **List of notifications**: Notifications that are sent when the step goes into Pending Approval status.
* **Timeout**: The maximum time the step can stay in Pending Approval status.

## Live Example 
Click [here](https://pipelines.jfrog.io/ui/pipelines/myPipelines/Quickstarts/Approval_Gates_Pipeline?projectKey=quickstarts) to see this Global template in action.
