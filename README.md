Docker VSTS s2i Build image

Based on the Golang image, VSTS adds tools to build docker images.

Included tools:
* node.js
* aws-cli
* jq
* docker-squash
* source2image
* skopeo
* golang
* build-essentials
* mage

This image is designed to be used by VSTS as a build image.
