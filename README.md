# IJCAI2017
Decreasing Uncertainty in Planning with State Prediction

This repository contains test scripts for the results presented in the paper ["Decreasing Uncertainty in Planning with State Prediction"](https://www.ijcai.org/proceedings/2017/0282.pdf) by Senka Krivic, Michael Cashmore, Daniele Magazzeni, Sandor Szdemak and Justus Piater

Prerequisities
============

You need the ROSPlan repository
(follow the installation instructions [here](https://github.com/KCL-Planning/ROSPlan/wiki/a.-Installation) )
```
git clone https://github.com/clearpathrobotics/occupancy_grid_utils
git clone -b squirrel https://github.com/kcl-planning/ROSPlan.git
```
Additionally you will require Flex and MongoDB.
```
sudo apt-get install flex
sudo apt-get install mongodb
sudo apt-get install ros-indigo-mongodb-store
```

You also need the [squirrel-prediction repository](https://github.com/squirrel-project/squirrel_prediction) which represents the core method for predicting missing values in the planning state.
```
git clone https://github.com/squirrel-project/squirrel_prediction
```

Planning domains
============
- 'tidy-room', inspired by the problem of cleaning a child’s room of project [SQUIRREL](http://www.squirrel-project.eu/)
- 'courseadvisor', adapted from [Guerin et al.](https://orff.uc3m.es/bitstream/handle/10016/14914/proceedings-WS-IPC2012.pdf?sequence=1)
- 'mars-rovers', a multi-robot version of the navigation problem of [Cassandra et al.](http://people.csail.mit.edu/lpk/papers/iros96.ps) 
- 'persistent-auv', described by [Palomeras et al.](https://www.springerprofessional.de/en/toward-persistent-autonomous-intervention-in-a-subsea-panel/10930422)
 
 These domains are contained in this repository under [domains_accuracy](https://github.com/Senka2112/IJCAI2017/tree/master/domains_accuracy)

Problems defined for evaluation with conditional planning are given under [domain_problem_complexity](https://github.com/Senka2112/IJCAI2017/tree/master/domain_problem_complexity)

Runing the tests scripts
========================



Additional info
===============

The version of the MMMVR framework which does not recquire ROS can be found at [mmr_mmmvr](https://iis.uibk.ac.at/software/mmr_mmmvr).


