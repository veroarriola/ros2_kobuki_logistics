# ros2_kobuki_logistics
Demos en escenarios de RoboCup Logistics pero utilizando la Kobuki como robot base.

## Prerrequisitos

Clonar en ```src``` los repos:
* https://github.com/veroarriola/ros2_kobuki
* https://github.com/veroarriola/gz_rcll

## Compilar

Para compilar sólo este paquete:

```
colcon build --packages-select ros2_kobuki_logistics
```

# Demo

Invocar:

```
ros2 launch ros2_kobuki_logistics defaultworld_kobuki.launch.py
```
