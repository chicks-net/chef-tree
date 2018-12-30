# chef-tree

[![Open Source Love png2](https://badges.frapsoft.com/os/v2/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![GPLv2 license](https://img.shields.io/badge/License-GPLv2-blue.svg)](https://github.com/chicks-net/chef-tree/blob/master/LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-no-red.svg)](https://github.com/chicks-net/chef-tree/graphs/commit-activity)

chef dependencies in a tree

## usage

	knife deps roles/FOO.json --remote --tree | chefdeps2tree > chef.dot
	dot -Tpng chef.dot > chef.png

## requires

* perl 5
* graphviz
* `knife` configured to work with your cookbooks
