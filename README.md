# Puppet Snippets for the CloudFormation

## Installation

Install using Sublime Package Manager. Otherwise you can clone this repository and symlink the cloned folder. This way you can modify the snippets and contribute back.

On Mac your Sublime package resides somewhere like,

`/Users/abhishektiwari/Library/Application Support/Sublime Text 2/Packages`

Create symlink,

	cd /Users/abhishektiwari/Library/Application Support/Sublime Text 2/Packages
	ln -s /Users/abhishektiwari/WorkSpace/SublimeSnippets/cloudformation .

where `/Users/abhishektiwari/WorkSpace/SublimeSnippets/cloudformation` is location of cloned repo.

## Supported Completion

### Template Declaration

CloudFormation templates have six main sections. Only `Resources` section is required. The rest are optional.

* blank