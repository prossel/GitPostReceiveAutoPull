# Git post-receive auto pull

This repos contains a helper script in bash to automatically pull a list of git working directories which branches match the received commits.

## Install

* Go to the repository hooks folder
* Clone GitPostReceiveAutoPull repository (ssh or https, choose your way)
* Create a symbolic link to the post-receive script in the hooks folder
  `ls -s GitPostReceiveAutoPull/post-receive`
* Make the post-receive file executable
  `chmod +x post-receive`
* Copy the sample config in the hooks folder
  `cp GitPostReceiveAutoPull/post-receive.config.sample post-receive.config`
* Edit your config
  `nano post-receive.config`

