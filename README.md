### urdfbot_description

#### Rviz2 screenshot

![Robot with arm](assets/urdf-robot-with-arm.png)  

#### Calibration element illustration

The following is a conceptual representation of the `<calibration />` element in the base-head joint.
 
```
|          switch
|        deactivated
|      ___________________             <- Falling edge (-1.5 radians)
|     /
|    /
|   /
|  /
| /_______________________             <- Joint movement direction
|                          \
|                           \
|                            \
|                             \        <- Rising edge (1.5 radians)
|                              -----------------------
|                                        switch
|                                      activated
```

