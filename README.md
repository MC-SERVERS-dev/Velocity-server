> [!CAUTION]
> **These plugins are no longer supported, Do not use them for any personal intentional needs.**


# Velocity-server
Host a velocity server...for free!

## Making the Github Codespaces with 16GB RAM and 4CPUs
To make the codespaces, make sure to access from https://github.com/codespaces.

## Installing Java
```bash
sudo apt update -y & sudo apt full-upgrade -y & sudo apt autoremove -y & sudo apt auto-clean -y
```
```bash
sdk install java 17.0.9-amzn
```
> write "y" without " and MAKE SURE TO WRITE y

## Make 3 tabs
* Server - > First Tab
* Velocity - > Second Tab
* Limbo - > Third Tab

## Commands for server (backend)
```bash
cd server
chmod +x server.sh
./server.sh
```
## Commands for velocity (proxy)
```bash
cd velocity
chmod +x velocity.sh
./velocity.sh
```
## Commands for limbo (login)
```bash
cd limbo
chmod +x limbo.sh
./limbo.sh
```

## FAQ

#### How to turn off the Github Codespaces?

1.) Go to https://github.com/codespaces

2.) then click the 3 dots and turn off

#### How to be an operator/admin in the server?

1.) Go to the Server/Backend - > First tab

2.) then type "op username" without "" and change the username to yours

> Please credit [IsmaelTech](https://www.youtube.com/@ismaeltechI?sub_confirmation=1)
> Also credit MC-SERVERS-DEV for the collection of servers.
