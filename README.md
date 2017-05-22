# IJCAI2017
Decreasing Uncertainty in Planning with State Prediction

This repository contains test scripts for the results presented in the paper "Decreasing Uncertainty in Planning with State Prediction" by Senka Krivic, Michael Cashmore, Daniele Magazzeni, Sandor Szdemak and Justus Piater

Prerequisities
============

You need the ROSPlan repository
(follow the installation instructions here: https://github.com/KCL-Planning/ROSPlan/wiki/a.-Installation )
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

You also need the squirrel-prediction repository (https://github.com/squirrel-project/squirrel_prediction) which represents the core method for predicting missing values in the planning state.
```
git clone https://github.com/squirrel-project/squirrel_prediction
```

Planning domains
============



Runing the tests scripts
========================


Additional info
===============

The version of the MMMVR framework which does not recquire ROS can be found at https://iis.uibk.ac.at/software/mmr_mmmvr


