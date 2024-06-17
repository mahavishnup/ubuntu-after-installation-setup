# ubuntu-after-installation-setup

### Installation deb packages

```shell
sudo dpkg -i ./*.deb;
```
### 
```shell
sudo apt -i ./*.deb;
sudo apt clean;
sudo apt update;
sudo apt upgrade;
sudo apt list --upgradable;
sudo apt upgrade -y;
sudo apt dist-upgrade;
sudo apt dist-upgrade -y;
sudo apt dist-upgrade -Vy;
sudo apt full-upgrade -y;
sudo apt autoremove;
sudo apt autoclean;
sudo add-apt-repository ppa:ondrej/php;
sudo apt-get update;
sudo add-apt-repository -y ppa:teejee2008/ppa;
sudo apt-get update;
sudo apt install net-tools;
sudo apt-get install ufw -y;
sudo ufw enable;
sudo ufw reload;
sudo ufw allow ssh;
sudo ufw status;
sudo apt install vlc gimp gparted 0ad;
sudo sed -i s/geteuid/getppid/g /usr/bin/vlc;
sudo apt install ubuntu-restricted-extras;
sudo apt install gnome-tweaks;
sudo apt install gnome-shell-extensions;
sudo apt install chrome-gnome-shell;
sudo apt install timeshift;
sudo apt install preload;
sudo apt install tlp tlp-rdw;
sudo apt install bleachbit;
sudo apt install tor torbrowser-launcher;
sudo apt install gdebi;
sudo apt-get install git;
sudo snap install whatsdesk;
sudo snap install telegram-desktop;
sudo apt install wine winetricks;
sudo apt install steam;
sudo apt-get install openjdk-11-jdk;
sudo apt install rar unrar p7zip-full p7zip-rar;
sudo apt install python3-pip python3;
sudo ufw enable;
sudo apt-get install gufw;
sudo apt-get install synaptic;
sudo apt-get install tlp tlp-rdw;
sudo systemctl enable tlp;
sudo apt-get install wine64;
sudo apt-get install flatpak;
sudo apt-get install gnome-software-plugin-flatpak;
sudo add-apt-repository ppa:gerardpuig/ppa;
sudo apt update;
sudo apt install nginx;
sudo apt install -y nginx;
sudo ufw app list;
sudo ufw allow 'Nginx HTTP';
sudo ufw status;
sudo systemctl enable nginx;
sudo systemctl start nginx;
sudo apt install -y php8.3-fpm php8.3-cli php8.3-gd php8.3-mysql php8.3-pgsql php8.3-imap php8.3-mbstring php8.3-xml php8.3-curl php8.3-bcmath php8.3-sqlite3 php8.3-zip php-memcached php8.3-common php-xdebug php8.3-{cli,imap,bcmath,bz2,intl,gd,mbstring,mysql,zip};
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === 'dac665fdc30fdd8ec78b38b9800061b4150413ff2e3b6f88543c636f7cd84f6db9189d43a81e5503cda447da73c7e5b6') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"
sudo mv composer.phar /usr/local/bin/composer;
composer global require "laravel/installer";
sudo nano ~/.bashrc;
export PATH="~/.config/composer/vendor/bin:$PATH"
source ~/.bashrc;
sudo service php8.3-fpm restart;
sudo apt install mysql-server -y;
sudo mysql_secure_installation;
sudo mysql -u root -p;
USE mysql;
CREATE DATABASE laravel;
CREATE USER 'newuser'@'localhost' IDENTIFIED BY 'password';
GRANT ALL PRIVILEGES ON *.* TO 'newuser'@'localhost';
FLUSH PRIVILEGES;
sudo systemctl enable tlp;
sudo apt update;
sudo apt install apache2;
sudo ufw app list;
sudo ufw allow 'Apache';
sudo ufw status;
sudo systemctl enable apache2;
sudo apt update;
sudo apt install redis-server;
sudo nano /etc/redis/redis.conf;
supervised systemd
sudo systemctl restart redis.service;
sudo apt install curl;
curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg;
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null;
sudo apt update;
sudo apt install gh;
curl -sL https://deb.nodesource.com/setup_20.x -o nodesource_setup.sh;
sudo nano nodesource_setup.sh;
sudo bash nodesource_setup.sh;
sudo apt-get install -y nodejs;
sudo apt autoremove;
sudo apt-get install gcc g++ make;
sudo apt-get update && sudo apt-get install yarn;
sudo apt-get update;
mkdir ~/.npm-global;
npm config set prefix '~/.npm-global';
sudo nano ~/.profile;
export PATH=~/.npm-global/bin:$PATH
source ~/.profile;
npm install -g pnpm;
curl -fsSL https://bun.sh/install | bash -s "bun-v1.1.6";
sudo nano ~/.bashrc;
export PATH=~/.bun/bin:$PATH
source ~/.bashrc;
npm install -g jshint;
npm install -g expo-cli;
npm install -g @vue/cli @vue/cli-service-global;
sudo ufw reload;
#ssh mahavishnu@mahavishnu;
#ssh-keygen;
#/home/mahavishnu/.ssh/id_rsa.pub;
sudo apt update;
sudo apt install nginx -y;
sudo apt install software-properties-common -y;
sudo add-apt-repository ppa:ondrej/php;
sudo apt install php8.3-fpm php8.3-common php8.3-dom php8.3-intl php8.3-mysql php8.3-xml php8.3-xmlrpc php8.3-curl php8.3-gd php8.3-imagick php8.3-cli php8.3-dev php8.3-imap php8.3-mbstring php8.3-soap php8.3-zip php8.3-bcmath -y;
wget -c https://files.phpmyadmin.net/phpMyAdmin/5.0.2/phpMyAdmin-5.0.2-english.tar.gz;
tar xzvf phpMyAdmin-5.0.2-english.tar.gz;
sudo mv phpMyAdmin-5.0.2-english /usr/share/phpmyadmin;
sudo ln -s /usr/share/phpmyadmin /var/www/html;
#Firefox Tweaks:
about:config
layers.acceleration.force-enabled
gfx.webrender.all
#Change DNS:
8.8.8.8,8.8.4.4
sudo apt clean;
sudo apt update;
sudo apt upgrade;
sudo apt upgrade -y;
sudo apt dist-upgrade;
sudo apt dist-upgrade -y;
sudo apt dist-upgrade -Vy;
sudo apt full-upgrade -y;
sudo apt list --upgradable;
sudo apt autoremove;
sudo apt autoclean;
sudo reboot;
sudo apt-add-repository universe;
sudo apt install gnome-tweak-tool;
sudo apt install gnome-shell-extensions;
sudo apt install dconf-editor;
sudo ln -s /home/mahavishnu/Downloads /usr/share/themes;
sudo cp -r /home/mahavishnu/Downloads/* /usr/share/themes;
sudo cp -r /home/mahavishnu/Downloads/Cupertino-Catalina /usr/share/icons;
sudo rm -rf *;


https://computingforgeeks.com/install-phpmyadmin-on-kali-linux/ 
https://bishrulhaq.com/tutorials/installing-nginx-and-phpmyadmin-on-ubuntu-18-04/

https://laravel-news.com/media-library-pro

laravel new trytrabby-extranet --jet --git --branch="main" --github="--private" 

laravel new trytrabby --git --branch="main" --github="--private" 

laravel new laravel-stisla-jetstream-admin-dashboard-pro-kits --jet --stack="livewire" --teams --force --git --branch="master" --github="--public" 


laravel new andamanroom --jet --stack="livewire" --teams --git --branch="master" --github="--private"

```
