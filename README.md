# Linux virtualization & Networking lab

Goals:
- Build multi-VM linux lab using Oracle VirtualBox.
- Use a dual-network architecture (NAT + Host-only).
- Configure an isolated internal VM network.
- Observe difference between Redhat and Debian in setting up.


![Network Diagram](./diagram.png)


### Create Fedora 42 virtual machine:
[See the video](https://drive.google.com/file/d/1peifxm1mVv_Fy3g66b41oG1k-Oh-qjyG/view?usp=drive_link)
- 1- Start VirtualBox and click on "New".
- 2- Choose a name and a folder for VM assets.
- 3- Select ISO file and click on next.
- 4- Modify base memory and processors or go by default.
(increased the cpu to 2 for package management and performance)
- 5- Create at least 15GB of virtual disk for updates and additional files.
- 6- Click on finish and do the same for ubuntu server.


### Fedora 42 installation:
[See the video](https://drive.google.com/file/d/1xIpP7NCAKFVAHz1nHfgnRixg47ZxlKS5/view?usp=drive_link)
- 1- Click on next until seeing installation summary page.
- 2- Go on installation destination, choose the created virtual disk.
- 3- Enable root account for root previlages or create a new user.
- 4- Click begin the installation.
