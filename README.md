Task 1


mkdir Animals

cd ~/Animals

cat > home_animals

dogs

cats

hamsters
C^

cat > pack_animals

horses

camels

donkeys
C^

cat home_animals pack_animals > animals

cat animals

mv animals human_friends

ls 


Task 2


cd ..

mkdir Nursery

cd ~/Animals

mv human_friends ~/Nursery

cd ~/Nursery

ls


Task 3


sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb

sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb

sudo apt-get update

sudo apt-get install mysql-server


Task 4


sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.1013~3-0~ubuntu-jammy_amd64.deb

sudo dpkg -i docker-ce-cli_20.10.133-0ubuntu-jammy_amd64.deb

sudo dpkg -r docker-ce-cli
