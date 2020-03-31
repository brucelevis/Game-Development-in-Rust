# Game Development in Rust

windows 64位 环境：

1. https://www.libsdl.org/download-2.0.php 下载 SDL2-devel-2.0.12-VC.zip

2. 下载完解压，SDL2.lib，SDL2main.lib，SDL2test.lib 把3个lib文件放入，
    .rustup\toolchains\nightly-x86_64-pc-windows-msvc\lib\rustlib\x86_64-pc-windows-msvc\lib

3. SDL2.dll，放入Cargo.toml同级目录即可

运行：

cargo run --example 01_window