# Game Development in Rust
 
**windows 64位 环境：**

1. https://www.libsdl.org/download-2.0.php 下载 SDL2-devel-2.0.12-VC.zip

   下载完解压，SDL2.lib，SDL2main.lib，SDL2test.lib 把3个lib文件放入，
   .rustup\toolchains\nightly-x86_64-pc-windows-msvc\lib\rustlib\x86_64-pc-windows-msvc\lib

   SDL2.dll，放入Cargo.toml同级目录

2. https://www.libsdl.org/projects/SDL_image 下载 SDL2_image-devel-2.0.5-VC.zip

   下载完解压，SDL2_image.lib 放入，
   .rustup\toolchains\nightly-x86_64-pc-windows-msvc\lib\rustlib\x86_64-pc-windows-msvc\lib

   文件夹内dll，放入Cargo.toml同级目录

**运行：**

cargo run --example 01_window