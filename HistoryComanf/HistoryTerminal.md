## Task 1
    
cd ~/Kennel    
cat > "Домашние животные.txt"    
cat > "Вьючные животные.txt"  
cat "Домашние животные.txt" "Вьючные животные.txt" > "Животные.txt"    
cat "Животные.txt"     
mv "Животные.txt" "Друзья человека.txt"
mkdir pitomnic
mv "Друзья человека.txt" /home/alinaas/pitomnik
cd pitomnik
ls       

## Task 2
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb    
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb    
sudo apt-get update    
sudo apt-get install mysql-server    

## Task 4
sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb    
sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb    
sudo dpkg -r docker-ce-cli    