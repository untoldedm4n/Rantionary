Rantionary
=========
[![Build status](https://ci.appveyor.com/api/projects/status/p3hejok9vys7agkn?svg=true)](https://ci.appveyor.com/project/TheBerkin/rantionary-4x1ls)

This is the official dictionary for use with [Rant](http://github.com/TheBerkin/Rant).

The latest .rantpkg build can be downloaded from [AppVeyor](https://ci.appveyor.com/project/TheBerkin/rantionary/build/artifacts).

##Resources

To learn the Rant dictionary file format, see [this article](http://rantlang.github.io/dictionaries.html).

Some tables use Diffmark to save space and make entries more readable. Read about Diffmark [here](https://github.com/TheBerkin/Diffmark/blob/master/README.md).

##Contribute

**Contributions are welcome.** I love new words! If you want to add something, be it big or small, send a pull request and I'll get to it within a couple days at the most.

##NSFW content

These dictionaries contain potentially objectionable content. Such entries should *always* be placed under a `nsfw` class. Rant will hide this class by default when loading dictionaries, but if you want to include them in queries without an explicit filter, do either of the following:
```cs
// From RantDictionary
myDictionary.IncludeHiddenClass("nsfw");

// From RantEngine
engine.Dictionary.IncludeHiddenClass("nsfw");
```

##License (or lack thereof)

These files are made available publicly without license or restriction. Use them in any way you wish.
