# CMake template project for STM32F103C8T6 development board (AKA blue pill)

This project should be added as a submodule to you git repo, with a command like:
```
git submodule add git@github.com:mixaz/stm32f1-ll.git
```
Copy CMakeLists.txt from `stm32f1-ll/example` folder to your project root and modify for your project structure. Currently `example/CMakeLists.txt` builds blink application:
```
cd example
./cm.sh
cd out
make
```
It builds STM32 firmware in blinky.elf file, you can flash it with command:
```
openocd
```

You can find more details in README from upstream repo: [README.org](README.org)

