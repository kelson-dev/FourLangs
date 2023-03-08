# Hello, World!

```csharp
Console.WriteLine("Hello, C#!");
```

In C# text is printed to the console using the `Console` object and a `Write` method. This example uses `WriteLine` which adds a "new line" character to the end of your text automatically for you.

A "method" is a kind of "function" which exists on an "object".

The `Console` object is `static`, meaning there is only 1 per running program.

The text you pass to the `WriteLine` method starts and ends with `"` characters. Those `"` quote characters are not included in the text that gets printed, instead they are how you tell C# where your text data starts and where it ends.



Notes for your 2nd playthrough:
 1. `Console` exists in the `System` namespace. You don't need to import that namespace because it is imported by default if `<ImplicitUsings>enable</ImplicitUsings>` exists in your `.csproj` file. If ImplicitUsings are not enabled then you would need to specify `System.Console` to access it.
 2. Traditionally C# programs needed you to create a "Program" class with a "Main" method as the entry point of your program. That still exists, but modern C# knows how to create it automatically for you if you don't do it yourself.