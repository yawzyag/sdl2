How to install SDL2:

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/SDL_Logo.svg/766px-SDL_Logo.svg.png)

> Use this commands in a Debian derivative like Ubuntu

# Install sdl2
    sudo apt install libsdl2-dev libsdl2-2.0-0 -y;

# Install sdl image
    sudo apt install libjpeg9-dev libwebp-dev libtiff5-dev libsdl2-image-dev libsdl2-image-2.0-0 -y;

# Install sdl mixer
    sudo apt install libmikmod-dev libfishsound1-dev libsmpeg-dev liboggz2-dev libflac-dev libfluidsynth-dev libsdl2-mixer-dev libsdl2-mixer-2.0-0 -y;

# Install sdl true type fonts
    sudo apt install libfreetype6-dev libsdl2-ttf-dev libsdl2-ttf-2.0-0 -y;
# Compile with
    gcc <file_name> `sdl2-config --libs --cflags` -ggdb3 -O0 --std=c99 -Wall -lSDL2_image -lm -o <file_output_name>
