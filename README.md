# node
Taiko
image

Requirements:

2 - 4 CPU 

4GB RAM 

50 GB SSD 

Setup:
Enter commands one by one

sudo apt update  


sudo apt upgrade 


apt install docker-compose 


sudo apt-get update && sudo apt install jq && sudo apt install apt-transport-https ca-certificates curl software-properties-common -y && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin && sudo apt-get install docker-compose-plugin 

Clone the repository

git clone https://github.com/taikoxyz/simple-taiko-node.git 

cd simple-taiko-node 

Run it on a separate screen:

screen -S rues 

Go in and make adjustments.:

cp .env.sample .env 

nano .env 

Before continuing with this part,
create a metamask from scratch get faucet, bridge

The screen that will open when you enter the command
After opening, we come to the bottom with the arrow keys.

Make ENABLE_PROPOSER 'true '

L1_PROPOSER_PRIVATE_KEY= We get the private key from the metamask m

in this section Metamask 0x Wallet Address will be L2_SUGGESTED_FEE_RECIPIENT=

CTRL + X + Y

image

Run node:

docker compose up 

Your Node is running:
image

No incentive announcement yet
