## SC-56B向けTWRPデバイスツリー
こちらのデバイスツリーを日本向けに書き換えました
(https://github.com/aHVzY2g/twrp-device-samsung-a22x)
```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_a22x-eng
make recoveryimage
```
Odin3とかでFlashして使ってください。  
fastbootdが使えるようになるのでsystem.imgを使ったROM焼きができるようになります
