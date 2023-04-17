### Simple Guide for use generator Pay For Blob Celestia

Link Demo : https://blockspace.cel.konsortech.xyz/


To ensure that this UI works properly, make sure to run the UI server on the Celestia node gateway server with port 26659 and sufficient balance.
or you can change the default port in config   .env file to listen port of your node


## Generate 

![Screenshot 2023-04-12 at 04 49 58](https://user-images.githubusercontent.com/112930581/232412021-b6ef2e72-3d01-46f2-9973-0152197f3e62.png)


## Result For PFB
![Screenshot 2023-04-12 at 04 49 58](https://user-images.githubusercontent.com/112930581/232412254-a5ed26f2-16ae-415f-8233-143d85347c61.png)



Step For Installation


```bash 
curl http://deb.nodesource.com/setup_lts.x | sudo bash -

sudo apt install git nodejs -y

```

``` bash
apt install npm

npm install child_process

npm install express
```

```bash
git clone https://github.com/Dexanode/celestia-blob
``` 

```bash
cd celestia-blob
```
# running inside screen 
```
screen -S celestia
```
```
node main.js
```
