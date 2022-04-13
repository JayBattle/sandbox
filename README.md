# sandbox
An Ubuntu container preloaded with useful command line tools.

## startup
cd /{REPO}
docker build -t sandbox .
docker run -it --privileged=true --name sandbox sandbox 