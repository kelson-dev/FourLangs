
# Installation

Get the latest rustup-init program from the official downloads page - currently: https://www.rust-lang.org/tools/install

On Windows, you may need to install the "Visual Studio C++ Build tools" when prompted to do so.

# Try it out
After installation, open a **new** [command line](https://en.wikipedia.org/wiki/Command_line) and type the command `cargo --version`. You should be greated with something like this:
```
cargo 1.67.1 (8ecd4f20a 2023-01-10)
```

Then switch your [working directory](https://en.wikipedia.org/wiki/Working_directory) to the `FourLangs/Rust/001_Hello` directory included with these lessons and run `cargo run`. The result should be something like this:
```
   Compiling hello v0.1.0 (~\FourLangs\Rust\001_Hello)
    Finished dev [unoptimized + debuginfo] target(s) in 0.27s
     Running `target\debug\hello.exe`
Hello, Rust!
```

Notice there is extra output from `cargo` that occurs before the output from our program ("Hello, Rust!"). The output from `cargo` is about [compiling](https://en.wikipedia.org/wiki/Compiler) our program before it ran it. That compiled program is now available in the new `FourLangs/Rust/001_Hello/target/debug/` folder and is named `hello.exe`. If you run `hello.exe`[^1] from your command line you will see just the program output, like this:
```
Hello, Rust!
```

You are now able to run the sample Rust programs!

# Trouble shooting

If after succesfully running the installer you enter the command `cargo` and get a message something like `'cargo' is not recognized as an internal or external command,
operable program or batch file.` then try the following steps:
 1. Close and re-open the program you ran the command from
 2. If the problem persists, restart your computer
 3. If the problem persists, manually check that the installed cargo executable was added to your [PATH](https://en.wikipedia.org/wiki/PATH_(variable)) and then start the trouble shooting steps again at 1.

If it still isn't working or you don't know how to do step 3 then at this point you will need to seek out specific help from someone you trust.


[^1]: Naming executable files with the `.exe` extension is a Windows specific convention. On macOS or Linux the file might have no extension at all, so if you see a file named just `hello`, run that. 