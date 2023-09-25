# linux
Script linux

php -v

sudo dpkg --remove php74p-fpm
sudo dpkg --remove php74-fpm

sudo apt --fix-broken install

sudo rm -rf /etc/php/php74

sudo apt remove php74-fpm php74p-fpm

sudo apt purge php7.4

sudo apt purge php74

sudo apt autoremove

dpkg -l | grep php7

sudo apt purge php74*

systemctl list-units | grep php

sudo systemctl status php74-fpm.service

sudo update-alternatives --set php /usr/bin/php7.4

disable php 7.2

sudo systemctl stop php7.2-fpm

sudo systemctl disable php7.2-fpm


sudo systemctl enable php7.4-fpm
sudo systemctl start php7.4-fpm
