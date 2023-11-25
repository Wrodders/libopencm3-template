Easy "clone and go" repository for a libopencm3 based project.

# Instructions
 1. git clone --recurse-submodules https://github.com/Wrodders/libopencm3-template 
 2. cd libopencm3
 3. make -C libopencm3 # (Only needed once)
 4. .. && cd Firmware
 5. make
 6. make flash

If you have an older git, or got ahead of yourself and skipped the ```--recurse-submodules```
you can fix things by running ```git submodule update --init``` (This is only needed once)

# Directories
* Firmware contains Project and setup directories 
* libopencm3 contains source code of libopencm3 project

# As a template
You should replace this with your _own_ README if you are using this
as a template.
