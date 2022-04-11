# Stylr
### Software to allow you to code how you want no matter what

Imagine working for years reading and writing code in a particular way until you've changed jobs.  Now you have to retrain yourself to read and write code in a different way (albeit slightly different).  Is this the end of the world?  I don't think it is but I did wonder what it would be like to not have to worry about that anymore.  Wouldn't it be nice to live in a world where you can read and write code how you want no matter what?  That's what `Stylr` aims to do!  Software that allows different people on the same team having their own unique style and not clashing with each other.  A codebase where it always looks how YOU want it to...even if other people write in a different way than you do.

Are you somebody that likes to look at code like below?
```cs
public void MyMethod(int arg1, int arg2) {
  if (arg1 is 5) {
    Console.WriteLine("First argument is 5!");
  }
  
  if (arg2 is 10) {
    Console.WriteLine("Second argument is 10!");
  }
}
```
Then just write it that way!  When you write code like that I'll open the file and see it the way I want to...maybe like this
```cs
public void MyMethod( int arg1, int arg2 )
{
  if ( arg1 is 5 )
  {
    Console.WriteLine( "First argument is 5!" );
  }
  
  if ( arg2 is 10 )
  {
    Console.WriteLine( "Second argument is 10!" );
  }
}
```
Or maybe even something like this
```cs
public void
MyMethod(int arg1, int arg2)
{
  if (arg1 is 5)
  {
    Console.WriteLine("First argument is 5!");
  }
  // ...
}
```

All of those should be fine!  Let's not worry anymore about how we store our code but that the code is viewed in a way that keeps us developers as productive as possible.  By focusing on how the code is styled when we open it and not on how it is stored we ensure a sense of uniformity thoughout entire codebases.  That's because we don't store style.  We make sure to store the syntax instead and strip away any personal style associated with the code, applying the style the developer wants when they want to open it.

By doing this, we can make sure an entire codebase looks identical from a styling perspective and not have different styles clashing between files.  See the code how you want to see it.  Write code how you want to write it.
