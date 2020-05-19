To generate your own binaries:

1) Download on the same directory Dockerfile and script.sh files
2) Change the Releases you want to build in Dockerfile
3) run "Docker build -t builder ." to build a new docker images that will be used to build binaries
4) Run "docker run -v /path/to/save/bin:/data/ builder" .
5) Go to /path/to/save/bin and take your bin
