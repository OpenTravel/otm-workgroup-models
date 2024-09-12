# OTM Workgroup Models

The purpose of this repository is to provide temporary edit access to OpenTravel's OTM model repository
for workgroup collaboration. Groups will be able to create new OTM libraries and make edits to existing
ones. Once the workgroup's changes are complete, the updates can be submitted to the OpenTravel staff
for incorporation into the public OTM model repository.

## Instructions for Use

1. Fork this repository. The new fork will act as the working copy repository for the workgroup. If
   the working copy will be maintained in an environment outside of GitHub, you can also download a zip
   of its contents and create your own repository manually.

2. Each person who will be working with the OTM-DEx editor should clone the forked repository to their
   local environment.

3. Launch the OTM-DEx editor and create a new project. Then load the required libraries from the cloned
   repository on your local file system. DO NOT load the OTM libraries from the Repositories tab of OTM-DEx.

4. When edits are complete, commit the changes locally and push the updates to the remote Git repository
   (the fork you created).

5. If multiple people are editing the models, be careful not to work on the same libraries at the same time
   since this method of operation will not be protected from creating merge conflicts.

6. Once all of the workgroup's changes are complete and have been pushed to the forked Git repository,
   contact the OpenTravel staff to have the changes reviewed and incorporated into the main OTM model repository.
