
# Installation

Get the latest installer from the official downloads page - currently: https://dotnet.microsoft.com/en-us/download

# Try it out
After installation, open a **new** [command line](https://en.wikipedia.org/wiki/Command_line) and type the command `dotnet --version`. You should be greated with something like this:
```
7.0.100
```

The number should match the version of whatever the latest installer is when you are following these instructions.


Then switch your [working directory](https://en.wikipedia.org/wiki/Working_directory) to the `FourLangs/CSharp/001_Hello` directory included with these lessons and run `dotnet run`. The result should be something like this:
```
Hello, C#!
```

Notice that after executing `dotnet run` there are new folders in the project, named `bin` and `obj`. These were created by the [compiler](https://en.wikipedia.org/wiki/Compiler) as it built your program from the source code in the `001_Hello` folder. You can find that built program itself in the `FourLangs/CSharp/001_Hello/bin/Debug/net7.0/` folder. The file `Hello.exe`[^1] in that folder is your built program. The last folder will be named after the version of the SDK you installed, which you saw earlier when you ran `dotnet --version`. At the time that I am writing this guide that folder is named `net7.0` but it may be different for you, such as `net8.0` or `net9.0`.

To run the built program directly, you can run that built `Hello.exe` program from your command line, and should get output like:
```
Hello, C#!
```

You are now able to run the sample C# programs!


# Trouble shooting

If after succesfully running the installer you enter the command `dotnet --version` and get a message something like `'dotnet' is not recognized as an internal or external command,
operable program or batch file.` then try the following steps:
 1. Close and re-open the program you ran the command from
 2. If the problem persists, restart your computer
 3. If the problem persists, manually check that the installed dotnet executable was added to your [PATH](https://en.wikipedia.org/wiki/PATH_(variable)) and then start the trouble shooting steps again at 1.

If it still isn't working or you don't know how to do step 3 then at this point you will need to seek out specific help from someone you trust.


[^1]: Naming executable files with the `.exe` extension is a Windows specific convention. On macOS or Linux the file might have no extension at all, so if you see a file named just `Hello`, run that. 