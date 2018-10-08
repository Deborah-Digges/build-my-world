# build-my-world
Introduction to Gazebo project


## Instructions to build the plugin

```
cd /home/workspace/myrobot
mkdir build
cd build/
cmake ../
make # You might get errors if your system is not up to date!
 export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/home/workspace/myrobot/build
```


## Make the models loadable in Gazebo

```
export GAZEBO_MODEL_PATH=${GAZEBO_MODEL_PATH}:/home/workspace/myrobot/model
```

## Open the world

```
gazebo myrobot/world/myworld.world
```



