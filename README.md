# CS425 MP2 - Cryptocurrency

## Group member
Jianfeng Xia(jxia11), Cheng Hu(chenghu3)

## Environment
Go 1.11.4, Python 36

## Usage
* Log into group VMs and clone repository
* To build:
    `go build client.go`
* Run program:
    `./client.go PORT`
    Alternatively, use our Python3 script experiment.py to start multiple clients (starting a node every 0.5s) and write stdout to logfiles.
    Usage of Python script: python36 experiment.py [NUMBER OF CLIENTS]
* Plotting:
    We have also included scripts to analyze performance and generate plots. To run the scripts: 
    * `cd logs`
    * `python3 propagation_plot.py`
    * `python3 bandwidth_plot.py`
  	Note:
    1. Our plot scripts use `matplotlib` and `numpy`, we suggest to run those scripts on machine has those library.
    2. Because the log files are large(we use logs in the case of 100 nodes, 20 mesg/s), please be patient when running scripts.
    
