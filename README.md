Description
------------------
Create containers using Node.js and FFmpeg.
Build on the official Node.js docker repo with an additional fresh installation of the latest FFmpeg

How to use this image
------------------
Like the official Node.js image, just run `docker run thalesdigitalfactory/node-ffmpeg:12-buster-slim`, a container will be created with Node process running

How to build this image
------------------
Make sure that the ownership of docker-entrypoint.sh is set to 1000:1000 than run `docker build -t my-node-ffmpeg .`

Contribute
------------------
- [code repository](https://github.com/thalesdigitalfactory/node-ffmpeg)
- [report issues](https://github.com/thalesdigitalfactory/node-ffmpeg/issues)

License
------------------
View [license information](https://github.com/nodejs/docker-node/blob/12/LICENSE)  for Node.js or [license information](https://github.com/nodejs/node/blob/12/LICENSE) for the Node.js Docker project.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

Some additional license information which was able to be auto-detected might be found in the repo-info repository's [thalesdigitalfactory](https://cloud.docker.com/u/thalesdigitalfactory)/ directory.

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
