# docker

To install: ```sudo apt install docker.io```

To make Docker start automatically on system boot: ```sudo systemctl enable --now docker```

To make sure everything is working okay: ```sudo docker run hello-world```

Search for an image: ```sudo docker search term-goes-here```

Install an image: ```sudo docker pull image-name-goes-here```

To run an image: ```sudo docker run image-name-goes-here```

To stop an image: ```sudo docker stop image-name-goes-here```

To remove an image: ```sudo docker image rm -f image-name-goes-here```
