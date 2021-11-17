![SleepUINO_Logo_PreDev](https://user-images.githubusercontent.com/48091357/111156537-25298a00-8596-11eb-8726-1fe5cd7bed93.png)
# ESP_Action_Build_Scripts
ESP Action Build Scripts contains scripts to build Arduino ESP Projects in a GitHub Action 
For example have a look to [ESP_jQuery_Mobile_Interface Actions](https://github.com/hredan/ESP_jQuery_Mobile_Interface/actions)

# Add Scripts to your repository
If you want use the scripts, you can add it easily as submodule
```bash
git submodule add https://github.com/hredan/ESP_Action_Build_Scripts.git
```
# Script desciption
## build_sketch.sh
```
build_sketch.sh -h
Paramter:
 -c     CORE=esp8266 or esp32 (default esp8266)
 -b     BOARD e.g. d1_mini or d1_mini32 (default d1_mini)
 -f     CPU Frequence e.g. 80, 160 or 240 (default 160)
 -s     Sketch name (mandatory)!
 -v     core version (default last one)
 e.g. sh ./build_sketch.sh -s SKETCH_NAME
```
