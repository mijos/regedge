regedge
=====

A P2P container registry helper tool with the goal to enable each container node running this software to directly exchange container images with another container host or pull an image from multiple sources in parallel.

`I do not use the term Docker Image explicitly as this is just one supported format.`

The project is using a simple way of enabling a P2P exchange without complicated data structures and the usual overhead.

How it works?
* A daemon will be started which can be configured during run time and keeps the very basic logic about peers
* The client application will be capable to set and change configuration and initiate transactions or schedule repeated tasks

