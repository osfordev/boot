# OS For Developers Boot

This is workspace branch of multi project repository based on [orphan](https://git-scm.com/docs/git-checkout#Documentation/git-checkout.txt---orphanltnew-branchgt) branches.

Branches (sub-projects):

* `binary` - TBD
* `builder` - TBD

## Get Started

1. Clone the repository
	```shell
	git clone git@github.com:osfordev/boot.git osfordev.boot
	```
1. Enter into cloned directory
	```shell
	cd osfordev.boot
	```
1. Initialize [worktree](https://git-scm.com/docs/git-worktree) by execute following commands:
	```shell
	for BRANCH in binary builder; do git worktree add "${BRANCH}" "${BRANCH}"; done
	```
1. Open VSCode Workspace
	```shell
	code "OS For Developers Boot.code-workspace"
	```
