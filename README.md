Installing Rust

Before installing Rustlings, you need to have Rust installed. Visit www.rust-lang.org/tools/install for further instructions on installing Rust. This will also install Cargo, Rust's package/project manager.

    🐧 If you're on Linux, make sure you've installed gcc (for a linker).

    Deb: sudo apt install gcc. Dnf: sudo dnf install gcc.

    🍎 If you're on MacOS, make sure you've installed Xcode and its developer tools by running xcode-select --install.

Installing Rustlings

The following command will download and compile Rustlings:

cargo install rustlings

If the installation fails… (click to expand)
Initialization

After installing Rustlings, run the following command to initialize the rustlings/ directory:

rustlings init

Now, go into the newly initialized directory and launch Rustlings for further instructions on getting started with the exercises:

cd rustlings/
rustlings
