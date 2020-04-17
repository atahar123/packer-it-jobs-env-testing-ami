# Understanding packer

Packer creates images.

It needs to provision somehow and then in the end it just creates an image of a machine.

It can do this for Google cloud or AWS or other cloud provider it has integration with.

It can also provision the machine with Bash scripts or using configuration management tools such as Chef.

We will use Chef to run the provision, and tell it to go and make an image on AWS


## Image for testing environment
- needs to be provisioned by Chef
- needs to run all the packages
