# RobotSystem2020_illumination

ロボットシステム学の課題1をまとめたリポジトリ

## 目的

講義内で学んだLinux、ライセンスに関する知識をデバイスドライバの製作を通して確認する。

## LEDを使用したクリスマスツリーの装飾

[サンプルコード](https://github.com/ryuichiueda/robosys_device_drivers)を改良しクリスマスツリーに装飾したLEDを制御する。

## 動作環境

- Ubuntu 18.04
- Raspberry Pi 4 Model B

## インストール

次のコマンドでインストール
```
git clone https://github.com/HayatoKitaura/RobotSystem2020_illumination.git
```
```
cd RobotSystem2020_illumination
```
```
make
```
```
sudo insmod illumination_led.ko
```
```
sudo chmod 666 /dev/illumination_led0
```
## 実行

次のコマンドで実行
```
echo > 1 /dev/illumination_led0
```

## デモ動画

[デモ動画](https://youtu.be/j2hollR4jmU)
