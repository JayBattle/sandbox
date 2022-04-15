# sandbox
An Ubuntu container preloaded with useful command line tools.

## startup
cd /{REPO}
sudo docker build -t sandbox .
sudo docker run -it --privileged=true --name sandbox sandbox 