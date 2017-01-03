## Installation
```
ln -s $(pwd)/pico-bind /usr/local/bin
```

## Usage
Put your broken up PICO-8 project files in the `src` directory. Make a file called `_assets.p8` that includes the sprites, music, sfx, etc. generated by PICO-8. Run `pico-bind` from the root of the repository to "compile" your project files.

Run `pico-bind run` to compile and run the PICO-8 project in one swoop (on macOS).

See [the-staff-of-lewis](https://github.com/jessemillar/the-staff-of-lewis) for example project and file structure.

### Project Structure
```
repository
	src
```
