This project is to create a workflow to build BigBlueButton, the video conference software as a Docker image.

Before using any of the instructions, one should check Docker Preference settings.

For Docker Desktop systems, one must go into Docker Preference -> Resources and set Memory to 4Gb.  

install docker


- pull image from online repository

~~~shell
$ docker pull ubuntu:16.04
~~~

- pull image from local registry




- local registry

將docker-compose.yml放入文件夾,並保持5000端口的暢通

~~~shell
$ docker-compose -f docker-compose.yml up
~~~

則會以attach的方式開啟registry.  

接下來欲測試Volume
