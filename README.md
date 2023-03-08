# Four Langs Programming Course

This is a educational resource to help people who are learning programming for the first time. It is meant to be a secondary resource to use *along side* another method of learning programming to help do 2 things:
 1. Build an understanding of what concepts are common to "programming" vs what concepts are specific to the main language you are learning
 2. Provide lots of useful examples for practicing "code reading skills"

It is designed for self-study, but I plan on making companion videos going over the content for folks who learn better that way.

# Quick start

Check out the first prompt, [Prompts/001_Hello/Hello_World.md](./Prompts/001_Hello/), and follow it's Quick Links section to the sample program in each of the 4 languages.

# Tips on How to Learn From This Resource

- Use this **alongside another resource** like a youtube tutorial playlist, coding website, bootcamp, or university. This project should augment another learning source rather than being your main resource.
- **Don't stress** about not understanding something, always feel free to go try out a different sample or take a break.
- **Don't try and learn all 4 of these languages** at once, just treat the ones you aren't learning as interesting notes to aid in your understanding of your main language.
- **Explore and tinker!** Instead of just reading each sample, make changes to it and run with those changes to see how it effects the programs behavior. 
    - If you have learned how to use [debuggers](https://en.wikipedia.org/wiki/Debugger) then use them to step through the samples line by line! 
    - If you have learned how to use [Git](https://en.wikipedia.org/wiki/Git) then use it to switch between different versions of your changes. 
    - If you don't know about either of those things, **that's ok**! You can always just delete the entire folder and download it again to revert back to the original state.
- **Don't try to master each sample** before moving on. Instead make sure to occasionally go back and revisit samples you have looked at before as you learn more concepts from your main learning resource.

# Which Languages

The four languages I chose are `JavaScript`, `Python`, `Rust`, and `C#` (pronounced c-sharp). I chose these languages because they have a lot of similarities to each other *but also* lots of differences, making it an ideal combination for this comparitive approach to teaching.

They are also all extremely popular languages that any programmer could benefit from knowing.

# Navigating This Resource

I recommend just exploring the files to get a feel for how things are structured, but if you prefer to have it written out then here you go:

In the top folder there is a folder for each language, `CSharp`, `JavaScript`, `Python`, and `Rust`, as well as a `Prompts` folder. Each of these language folders will have a `Getting Started.md` document that you can read to learn how to install and use the required software for running the sample programs.

The sample programs are organized into folders such as `001_Hello`. The three digits at the start are to organize the samples by the recommended order for new programmers, but that order is strictly a recommendation, not a requirement. The sample number will exist in the folders for all 4 languages and the `Prompts` folder, so there is a JavaScript 001_Hello, a C# 001_Hello, a Rust 001_Hello, and a Python 001_Hello, and a Prompts/001_Hello folder. 

In the Prompts folder you will find details on what each sample is attempting to do, what it is teaching, and what additional resources you might want to check out to learn more.

For example:
```
/ FourLangs
--/ Prompts
----/ 001_Hello
----/ 002_Variables
      ...
--/ Python
----/ 001_Hello
----/ 002_Variables
      ...
--/ JavaScript
----/ 001_Hello
----/ 002_Variables
      ...
--/ Rust
----/ 001_Hello
----/ 002_Variables
      ...
--/ CSharp
----/ 001_Hello
----/ 002_Variables
      ...
```

Some samples will introduce specific programming concepts, and others will present puzzles or problems and show ways to solve that problem in each language.

Additionally some samples may have more than 1 solution for 1 or more of the languages.
For example for a hypothetical sample on calculating metrics, there might be a folder structure like this:

```
/ FourLangs
--/ Python
----/ 690_MetricsReporting_Loops
----/ 690_MetricsReporting_MapFilterReduce
--/ JavaScript
----/ 690_MetricsReporting_Loops
----/ 690_MetricsReporting_MapFilterReduce
--/ Rust
----/ 690_MetricsReporting_Loops
----/ 690_MetricsReporting_MapFilterReduce
--/ CSharp
----/ 690_MetricsReporting_Loops
----/ 690_MetricsReporting_MapFilterReduce
```

The fact that Python programmers use what they call "List Comprehensions" for the general concept of "map filter reduce" and that C# programmers use what they call "LINQ" for that same concept would be explained in the `Nodes.md` file of those specific samples.