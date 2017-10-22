Raspberry Pi Zero W 用 ROS Kinetic環境構築ファイル
====


## Requirement
gdebiコマンドを使用するので事前にインストールして下さい。
$ sudo apt-get install gdebi -y

## Usage
リリースからダウンロードしたファイルを使用して下さい。

## Install
$ unzip rpi-zerow-kinetic_X.X.X-X_armhf.zip
$ sudo gdebi rpi-zerow-kinetic_X.X.X-X_armhf.deb
$ sudo /opt/ros/kinetic/initialize.sh
