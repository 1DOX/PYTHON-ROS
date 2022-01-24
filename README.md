# Self-Driving Car System
2021년 2학기 객체지향모델링(로봇프로그래밍) 과목 팀 프로젝트로 수행한 자율 주행 시뮬레이션으로,
주어진 주행 시험장 환경의 트랙을 따라 주행하며 장애물과 충돌하지 않도록 자율 주행하는 로봇 구현.

2021-02 Robot Programming Project
- What is? : ROS(Robot Operating System) Project
- Project Name : Self-Driving(Autonomous Driving) Car(Robot)

## How To Launch
### Gazebo
**Case 1) Use roslaunch:**
```markdown
$ roscd deu_car
$ source ./gazebo_env.sh
$ roslaunch deu_car car_test.launch
```

**Case 2) Use .bashrc alias:**
```markdown
$ echo "alias car='roscd deu_car && source ./gazebo_env.sh && roslaunch deu_car car_test.launch''" >> .bashrc
$ car
```


### Python Source
**Execute Gazebo then execute .py file**
```markdown
$ rosrun deu_car bot_state_machine.py
```


## IDE & Tools

Ubuntu OS의 Docker를 이용한 가상 환경에서 Python, ROS, OpenCV 등을 이용하여 구현하였다.
* 개발 언어(Programming Language) : [Python](https://www.python.org/), [OpenCV](https://opencv.org/), [ROS](https://www.ros.org/)
* 개발 툴(Programming Tools/IDE) : [Docker](https://www.docker.com/), [VNC Viewer](https://www.realvnc.com/en/connect/download/viewer/)
* 운영 체제(Operating System) : [Ubuntu](https://ubuntu.com/)


<!-- USAGE EXAMPLES -->
## Project Demo

[![Self-Driving Car System DEMO](https://img.youtube.com/vi/MfgGUjT_nIw/0.jpg)](https://youtu.be/MfgGUjT_nIw)
