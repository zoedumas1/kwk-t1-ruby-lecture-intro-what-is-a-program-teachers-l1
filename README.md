---
tags: introduction, basics, lecture
language: ruby
type: video
---

# Ruby Lecture: Introduction - What is a Program?

<video controls width="100%">
  <source src="http://flatiron-videos.s3.amazonaws.com/ironboard/ruby/ruby-lecture-what-is-a-program/ruby-lecture-what-is-a-program.mp4" type="video/mp4" >
    The video accompanying this lab is best enjoyed on Learn.co
</video>

[MP4](http://flatiron-videos.s3.amazonaws.com/ironboard/ruby/ruby-lecture-what-is-a-program/ruby-lecture-what-is-a-program.mp4)

## Topics Covered:

* What is a program?
* The difference between interpreted and compiled programs.
* How to run a ruby program in your terminal
* The words that compose code: keywords, barewords, and data.

## Summary

### 1 - What's a Program?

All programs are just files on your computer filled with text. That text has a special syntax we call code. The programming language you're using defines the syntax of the code you are allowed to write. Programs are converted to machine code so that the computer can understand it. 

### 2 - Interpreted vs Compiled

Depending on the programming language you're using, it will either be a [compiled language](http://en.wikipedia.org/wiki/Compiled_language) or an [interpreted language](http://en.wikipedia.org/wiki/Interpreted_language). Compiled programs will first be converted to machine code and then you will be able to run the program. Interpreted languages will be interpreted and converted to machine code at run time.

### 3 - Running a Ruby Program

Once you have a ruby program as a file, like the example in `lib/a_ruby_program.rb`, you can run it through the ruby interpreter to execute it. Your ruby interpreter is accessible via the `ruby` command in your command line (assuming you have ruby install correctly).

```bash
ruby -v
ruby 2.2.2p95 (2015-04-13 revision 50295) [x86_64-darwin14]
```

When you type in `ruby -v` you should see the version of Ruby you are currently running.

To run the program from the root of this lab's directory 

### 4 - Words in a Program