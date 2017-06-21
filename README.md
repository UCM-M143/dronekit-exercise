# dronekit-exercise

## open a terminal and then install dronekit

```
sudo apt-get install python-pip python-dev python-numpy
sudo pip install dronekit
sudo pip install dronekit-sitl
sudo pip install MAVProxy
```

## Download dronekit source code with examples

```
cd /tmp
git clone https://github.com/dronekit/dronekit-python.git
```
## Understand and run examples
### Example: Vehicle State
Read following webpage to understand how it works
http://python.dronekit.io/examples/vehicle_state.html

Use following command to run it
```
cd /tmp/dronekit-python/examples/vehicle_state
python vehicle_state.py
```
### Example: Simple Go To (Copter)
Read following webpage to understand how it works
http://python.dronekit.io/examples/simple_goto.html

Use following command to run it
```
cd /tmp/dronekit-python/examples/simple_goto
python simple_goto.py
```

### Example: Mission Basic
Read following webpage to understand how it works
http://python.dronekit.io/examples/mission_basic.html

Use following command to run it
```
cd /tmp/dronekit-python/examples/mission_basic
python mission_basic.py
```

## Write your own program

Based on the [`Example: Vehicle State`](https://github.com/dronekit/dronekit-python/blob/master/examples/vehicle_state/vehicle_state.py), modify it so that it only prints Global Location

Here is an screenshot of an example output
