# Open Source Policy  
Zetta is founded on open source software. Here are policies governing how to contribute and use open source software within the company.

## Contributing  
* All code contributions should be made to repositories within Zetta’s GitHub
* Commits should be made with a Zetta email address (can be linked to an existing GitHub account, if you like). 
* New projects  
  * Initially set as private repositories
  * Requires approval from the Open Source Committee for open source release
* Patching existing projects
  * <=100 lines of code, does not require approval for release (fill out form?)
  * \>100 lines of code, requires approval from the Open Source Committee for open source release

## Using  
There are no restrictions on packages that may be used.

## Scenarios  
1. You need to use seung-lab/cloud-volume in a new ingest script. You find the appropriate repository within Zetta’s GitHub, or you create one and add your ingest script there. You use cloudvolume as a PyPi package.
1. While writing your ingest script, you realize that seung-lab/cloud-volume has a bug. If the repo hasn’t been forked to Zetta's GitHub, you go ahead and fork it. If it has been forked, you check to see if the bug has been fixed. If it hasn’t, you patch the bug with a one line fix, and commit with your Zetta email address. Since the patch is <100 lines, no approval is necessary -- just fill out the patch form (in process) to log that you made a change, then go ahead and issue your pull request.
1. You realize that seung-lab/cloud-volume requires a new feature. You add the feature in the forked version of the repo within Zetta's GitHub, and all your commits are made with your Zetta email address. When it’s ready for release, fill out the release request form (in process). The Open Source Committee will work with you to determine a release plan.

## The Open Source Committee  
### Changes to the policy and the committee  
The committee has the authority to make changes to the policy and changes to the committee
### Notice of policy changes  
If the committee makes changes to the policy, it must notify all users.
### Current members  
Tommy Macrina, <tmacrina@zetta.ai>
