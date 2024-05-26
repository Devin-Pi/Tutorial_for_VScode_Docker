# Tutorial for Vscode & Docker
This tutorial can help you learn how to use docker in VScode.

## Pre-requirments
- Download & install [VScode](https://code.visualstudio.com/)
- Download & install [Docker](https://docs.docker.com/engine/install/ubuntu/)
- Download & install [Nvida_Container_Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html)

## Usage

### Install extentions in VScode
- Docker, Dev Container.\
![1716637066377.png](http://rdpi.myds.me:9098/i/2024/05/25/6651cd8c222c0.png)
![1716637117064.png](http://rdpi.myds.me:9098/i/2024/05/25/6651cdf7905a9.png)

### Create & overwrite Dev Configuration Files

- Add the dev configuration files shown as follows:
1) Click the left bottom of the VScode and select `Add Dev Container Configuration Files`.
![1716637664941.png](http://rdpi.myds.me:9098/i/2024/05/25/6651cfe369e60.png)
2) Select `Docker Outside of Docker Compose`.
![1716637687995.png](http://rdpi.myds.me:9098/i/2024/05/25/6651cffaa90c3.png)
3) Then click `ok` until the `.devcontainer` folder was created. You can find there are 3 files in this folder. Based on your requirements, please overwrite these three files. Generally, using `devcontainer.json` and `dockercompose.yaml` can meet the requirements of the Deep Learning. We give a basic example shown as follows:

This is the `devcontainer.json`:
![1716637577353.png](http://rdpi.myds.me:9098/i/2024/05/25/6651cf8aab71a.png)
This is the `docker-compose.yaml`:
![1716637594582.png](http://rdpi.myds.me:9098/i/2024/05/25/6651cf9c1faed.png)
### Create & Open the container
After overwriting the files in `.devcontainer`, lets open the container.
- Click the left bottom of the VScode, and select `Reopen in Container` shown as follows:

![1716689565295.png](http://rdpi.myds.me:9098/i/2024/05/26/66529a9f26080.png)


Then a new window is created. Please watch the left bottom of VScode, the `DevConiner` will display. 
![1716691635198.png](http://rdpi.myds.me:9098/i/2024/05/26/6652a2b49d194.png)

Now, lets enjoy the Docker journey!😊


**Note**:You can find an example for `.devcontainer` in this link [.devcontainer](https://connectpolyu-my.sharepoint.com/:f:/g/personal/22123553r_connect_polyu_hk/ElH7Hds9M6tMgjTQsSI2EvIBir9huXZJh46qLVpHYVp4DQ?e=QRpnDh).

If you find our work useful in your research, please consider giving a star😊!
