## What is an External Node Classifier?

* An arbitrary script or application which can tell Puppet which classes a node should have
* An executable that can be called by puppet master
* Reference any data source you want, including some of Puppet’s own data sources
* Can be used in conjunction with other ENCs
    * Classes declared in each will be merged
* When compiling a catalog, all of the following is considered, in-order:
    * Classes specified in the node object it received from the node terminus
    * Classes or resources which are in the site manifest but outside any node definitions
    * Classes or resources in the most specific node definition in site.pp that matches the current node
