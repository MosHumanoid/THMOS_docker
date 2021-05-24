# THMOS_docker
Docker for 2021 Robocup

比赛服务器官方文档：
https://cdn.robocup.org/hl/wp/2021/05/v-hsc_server_specification_draft3b.pdf
比赛在亚马逊云服务器上进行，参赛队的软件需要通过docker image提交到服务器中，比赛时会从抽取docker image放入Robot VM实例（每个机器人一个服务器，将含有软件的docker image放入其中），Robot VM通过API server与webots比赛环境通讯。

Docker教程：https://www.runoob.com/docker/docker-container-usage.html
Docker image如何push到远程见官方文档。

Dockerfile根据bitbots的Dockerfile改写，保留了前面配环境的部分。
