# ChipAllegro
A Chip8 emulator using allegro5

##### Requirements:

- C++11 (Not tested with others)
- Allegro 5.0 ( <code>brew install allegro</code> if you are on macOS)

##### How to use:

It is mainly written in C++, so first of all compile it using:<br>
<code>g++ *.cpp -lallegro -lallegro_main -lallegro_primitives -o ChipAllegro -std=c++11</code>

And run it using: <code>./ChipAllegro <rom file></code>

##### Todo:

There is *a lot* to do:

- Input support (Initial support added on the [v.0.2-alpha](https://github.com/deople/ChipAllegro/tree/v0.2-alpha))

- Sound support

- Reduce graphical glitching

- Add support for +4k size rom

- document the code

  

