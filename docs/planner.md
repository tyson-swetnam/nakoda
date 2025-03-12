# Mission Planners

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## What are Ground Control Stations (GCS)?

The Nakoda and Mini-me drone both operated on [Ardupilot's Mission Planner](https://ardupilot.org/planner/docs/mission-planner-overview.html){target=_blank} software as its Ground Control Station (GCS) mission planning software.

GCS are necessary for monitoring on-board information, like remaining battery %, mission plan (survey, waypoints),  

We are testing both Mission Planner and QGroundControl as options for the GCS.

!!! Info "Ground Control Stations (GCS)"

    A ground station is typically run from a ground-based computer, tablet, or phone. It transmits wireless telemetry to teh UAS via an USB antenna.

    * [**Mission Planner**](https://ardupilot.org/planner/docs/mission-planner-overview.html) - Windows friendly, may not be fully Linux compatable.

    ![mission planner](https://ardupilot.org/planner/_images/mission_planner_screen_flight_plan.jpg)

    * [**QGroundControl**](https://qgroundcontrol.com/) - works in Linux, clean, modern look.

    ![qgroundcontrol](https://docs.qgroundcontrol.com/master/assets/connected_vehicle.BmASIvhv.jpg)

## Install Mission Planner

Mission Planner is ideally run on a Windows Laptop, but it can also be installed on Android and Linux.

[Mission Planner Installation Instructions](https://ardupilot.org/planner/docs/mission-planner-installation.html){target=_blank}

## Installing QGroundControl 

[Installation Instructions](https://docs.qgroundcontrol.com/master/en/qgc-user-guide/getting_started/download_and_install.html)


### Ubuntu installation

```sh
sudo usermod -a -G dialout $USER
sudo apt-get remove modemmanager -y
sudo apt install gstreamer1.0-plugins-bad gstreamer1.0-libav gstreamer1.0-gl -y
sudo apt install libfuse2 -y
sudo apt install libxcb-xinerama0 libxkbcommon-x11-0 libxcb-cursor-dev -y
```


Install (and run) using the terminal commands:

```sh
mkdir QGroundControl
cd QGroundControl
wget https://d176tv9ibo4jno.cloudfront.net/builds/master/QGroundControl-x86_64.AppImage
```

Download [QGroundControl.AppImage](https://d176tv9ibo4jno.cloudfront.net/builds/master/QGroundControl-x86_64.AppImage){target=_blank}

```sh
chmod +x ./QGroundControl.AppImage
./QGroundControl.AppImage  (or double click)
```

## Loading Firmware

## Plan Autonomous Mission

## MAVProxy

[MAVProxy](https://ardupilot.org/mavproxy/)