Raspberry Pi Zero W 用 ROS Kinetic環境構築ファイル
====

## Description
「ROSではじめるホビーロボット#06」で紹介したRaspberry Pi Zero W へROS Kinetic環境を簡単にインストールするためのdebパッケージです。   
releasからダウンロードしたファイルをインストールして下さい。   
リポジトリから取得する外部ファイルの更新などでエラーが発生する可能性があります。この場合は誌面を参考にエラーを解決して下さい。   

## Requirement
gdebiコマンドを使用するので事前にインストールして下さい。   
$ sudo apt-get install gdebi -y

## Usage
リリースからダウンロードしたファイルを解凍し使用して下さい。   

## Install
$ unzip rpi-zerow-kinetic_X.X.X-X_armhf.zip   
$ sudo gdebi rpi-zerow-kinetic_X.X.X-X_armhf.deb   
$ sudo /opt/ros/kinetic/initialize.sh   
