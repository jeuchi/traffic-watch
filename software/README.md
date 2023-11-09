# Software Stack

## Requirements

- CARLA simulator 0.9.13 (0.9.14 currently has a bug with the camera sensor)

- Python 3.7.9

## Setup
```
pip install -r requirements.txt
```

## Running CARLA
If you need to generate random license plates, this requires a source build of CARLA. Otherwise, the ready made binary is fine to use. Run CARLA binary for server hosting

### Manual Control
Run /third_party/manual_control.py

### Client Scripts
Inside /carla, there are various scripts to create events for training or testing

## Machine Learning
The scripts found in /ml are used to train various models used in the pipeline. Note that due to the amount of data collected,
these outputs are not saved in the repository. 