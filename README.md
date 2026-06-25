# Rust Installation Instructions

## About
This repo is just for me and other individuals that want to install Rust as simple as possible without having to rewatch a YouTube video.

This is a personal instruction manual to downloading Rust in my Windows machine.

## Dependencies
* Install the `rustup-init.exe` from [rust-lang.org](https://rust-lang.org/)
* Install `msys2` executable from [msys2.org](https://www.msys2.org/)

## Steps
1. Run the `msys2` binary and run the following commands.
```cmd
pacman -S mingw-w64-x86_64-toolchain
pacman -S base-devel
```

2. Next, run the `rustup-init.exe` file and proceed with the following instructions.
    1. Press `2` to select `Manually install the prerequisites`
    2. If asked to continue, press `y`
    3. Press `2` to select `Customize installation`
    4. For the `Default host triple` type `x86_64-pc-windows-gnu`
    5. Press `1` to select `Proceed with installation`

<br/>
> By now, the rust toolchain should be installed, run `rustc --version` to check if the installation was successful. If not, try closing the command prompt and reopening it.
>
> If not successful, try looking at this YouTube video: https://www.youtube.com/watch?v=92HoSWgsx-4
