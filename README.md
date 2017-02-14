[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/furi-git-prompt.svg)](https://hub.docker.com/r/rubygem/furi-git-prompt/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/furi-git-prompt.svg)](https://hub.docker.com/r/rubygem/furi-git-prompt/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/furi-git-prompt.svg)](https://hub.docker.com/r/rubygem/furi-git-prompt/)
[![Gem Downloads](https://img.shields.io/gem/dt/furi-git-prompt.svg)](https://rubygems.org/gems/furi-git-prompt/)
# furi-git-prompt

Auto-Generated Docker image for furi-git-prompt to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/furi-git-prompt`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/furi-git-prompt`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/furi-git-prompt`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/furi-git-prompt/)
