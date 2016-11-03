# chef-tree

chef dependencies in a tree

## usage

	knife deps roles/FOO.json --remote --tree | chefdeps2tree > chef.dot
	dot -Tpng chef.dot > chef.png

## requires

* perl 5
* `knife` configured to work with your cookbooks
