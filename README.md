# Git post-receive auto pull

This repository contains a helper script in bash to automatically pull a list of git working directories where current branche matches the received commits.

## Install

```bash
# Go to the repository hooks folder
cd .git/hooks

# Clone GitPostReceiveAutoPull repository
git clone https://github.com/prossel/GitPostReceiveAutoPull.git

# Create a symbolic link to the post-receive script in the hooks folder
ln -s GitPostReceiveAutoPull/post-receive

# Make the post-receive file executable
chmod +x post-receive

# Copy the sample config in the hooks folder
cp GitPostReceiveAutoPull/post-receive.config.sample post-receive.config

# Edit your config
nano post-receive.config

```
