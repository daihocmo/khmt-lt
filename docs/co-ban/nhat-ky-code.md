# Nhật ký code

Nhật ký code hay code diary/coding journal là chỉ việc mình sưu tầm các code snippets hay các kiến thức nhất định để sử dụng lại. Bạn chỉ cần xem thử một ví dụ về Code Diary là hiểu liền: [Code Diary của semicolonandsons](https://www.semicolonandsons.com/code_diary) hay [Lập trình Cheatsheet](https://duyk471.github.io/lap-trinh-cheatsheet/) của cá nhân mình.

Bài viết gốc: [The power of keeping a coding journal](https://www.thomasburette.com/blog/2014/06/25/the-power-of-keeping-a-coding-journal/)

---

_This post was inspired by the tool [jrnl](http://maebert.github.io/jrnl/index.html) which has been mentioned on hacker news._

An innumerable number of thoughts go through you head as you develop :

-   The pending issue you’ll get back to later
-   This design decision
-   The rejected algorithm alternative
-   That library that might be deprecated
-   This potential bug when the file is empty
-   The error case that could be handled better

What if you possessed a coding journal of all those fleeting thoughts?  
How immensely valuable would it be to go back at the end of the project and make sure all those issues that were pending when you thought of them have been handled properly:

-   The outstanding issue you forgot to implement
-   The clever design decision you need to document
-   The code comment for that code that could be replaced by a better algorithm
-   The library you forgot to upgrade
-   The bug you never fixed
-   The _TODO_ comment for that missing error handling

Well I’ve been keeping such journals when I code and it turns out to be immensely valuable!

## Keeping a thoughts journal

When I’m coding I keep a simple text file open somewhere that I fill with those _fleeting thoughts_. In practice what I write down are the **unsettled questions and red flags that pop in my mind**.  
I want to emphasize that the coding journal is not a todo file or code comment. It contains _things I have to think about_ not _things I have to do_. It contains thoughts that have no other place to go.In practice I found it does tend to duplicates the todo file as well as code comments but it contains much more than that.

A first I thought it would be really inconvenient and get in the way of me coding. But I’ve found in practice that it’s light and quick. With [tmux](http://tmux.sourceforge.net/) it’s a simple matter of typing a shortcut to reach the journal, typing the thought and typing another shortcut to go back to the code. The flow of thoughts is largely unaffected by the need to type it down.

It does takes a little bit of time at first as you tend to forget to write things down, especially after having been interrupted, but after a while it becomes an inherent part of your _flow_, a part of your thinking process.

## Reaping benefits

One benefit is the ability to jump back into a project, especially if some time has passed. A good practice is to commit everything at the end of the day. I must admit I rarely do that. The journal comes in handy to identify and jump back into the last piece of code worked on.

The great benefit of this journal comes towards the end of the development. I’ll go back to my coding journal and analyze every entry. Many of the entries will have been dealt with and me of no use.  
However many others become really useful.

The journal is a great tool to write the documentation. User level documentation as well as code documentation. Writing general documentation without the code journal is no problem: how to use this, how to do that. However there are many useful artifacts that can be derived from the coding journal. All the little bits and pieces you realize might be useful to people: the performance aspect, the corner case when doing that, the subtety in that step, the requirement,… It makes documentation much more complete.

Several entries of the journal will discover things that never were done or settled down. It gives you a safety net for the things you thought about but forgot (but doesn’t prevent things you forgot at all). Some of those items require immediate fix. The rest typically end up in a todo file or comment in the code. It can give me the sentiment that you are never done and that there always is something to fix or improve.

Once I’ve gone through all those entries I’ll have a solid sense of having settled everything down. No loose ends. No things forgotten. Using this technique I’ve been commended for being so ‘detailed oriented’. I’ll admit I’m not, no more than anyone else.

Another great advantage I didn’t anticipate is a hard to articulate **ease of mind** coming from having all the little lose end written down solidly somewhere. Your mind can let go of the myriad of pending little bits of thoughts. It knows it is written down and won’t be forgotten. Thinking of it it works like [GTD](https://en.wikipedia.org/wiki/Getting_Things_Done) in this respect.

## No silver bullet

The coding journal doesn’t prevent me writing from writing bugs. It helps me make sure I do not forget things I thought about but does not prevent me from missing things altogether.

I wouldn’t say that the coding journal is painless. Logging needs some effort, you’re always evaluating in your mind if you need to write this thing or that thing down. In fact it can be a hindrance in some cases and cause a form of analysis paralysis. You look at all the loose ends and wonder how you’ll ever tie everything down together.

It has never become a habit and I find myself tending to be reluctant to get into the logging thinking mode. I found I shy away from using the journal for small projects/tasks altogether.

---

## Tài nguyên

Có không ít các trang đã sưu tầm môt số lượng các Code Snippets để sử dụng lại (Mới chỉ dừng lại ở Code Snippets thôi).

- [1: Quicksnip](https://quicksnip.dev/)
- [2: Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/)
- [3: CSS Tricks](https://css-tricks.com/snippets/)
- [4: Snipplr](https://snipplr.com/)
- [5: Masscode](https://masscode.io/snippets/)
- [6](https://www.creative-tim.com/bits/)
- [7](https://gravitywiz.com/snippet-library/)
- [8](https://www.w3schools.com/jsref/default.asp)
- [9](https://codepen.io/)