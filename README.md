# SmartSketch

## Run

```shell
# /backend
docker-compose up --build 
```

localhost:8080

## Set Up

- You'll need to install the pretrained generator model for the COCO dataset into `checkpoints/coco_pretrained/`. Instructions for this can be found on the `nvlabs/spade` repo.

- Make sure you install all the Python requirements using `pip3 install -r requirements.txt` (in `/backend` folder).     

- Once you do so, you should be able to run the server using `python3 server.py`. It will run it on `0.0.0.0` on port 8080 (on `127.0.0.1` for Windows users). 


## Reference

- https://nvlabs.github.io/SPADE/
- https://arxiv.org/abs/1903.07291
- https://github.com/nvlabs/spade/

