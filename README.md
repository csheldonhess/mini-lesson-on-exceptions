# Mini-lesson on Exceptions in Python
Just a short (30 min) peer lesson on exceptions in Python, for CIT-129

**What's in this repository:**
* A PDF (text-searchable) with some quick hints/how to use exceptions
* The same PDF set up to print twice per page to save paper (not text-searchable)
* A Jupyter notebook with demonstration code

# Extension exercises for CIT-129:

We've all written some code this semester that would benefit from using exceptions. In particular, given that there's some network code and some work happening with files in most of our API projects, I think the very best possible extension exercise for all of us is to go back and refactor our API projects to use `with`/`as` and `try`/`except`/`else`/`finally`. 

If you'd like to see how I refactored mine, you're welcome to look at [my original code](https://github.com/csheldonhess/reporting-on-congress/blob/master/old_report.py) and [my refactored code](https://github.com/csheldonhess/reporting-on-congress/blob/master/report.py). (And if you have a ProPublica API key, you can clone my repo and confirm that both versions work just fine. The new one's a little better, actually, because I found an unrelated bug in my older code when I went back to edit it.)

If you don't want to work on your API project again for some reason&mdash;you burned yourself out on it, or it doesn't give you enough chances to play with refactoring&mdash;we've done other file manipulation in class. It's fine with me if you go back and add exception handling to the the jail data project, for instance. (But your API projects were all really good, so I kind of hope that's what you pick. 😁)

# Further reading:
* Very accessible intro to how exceptions are written in Python: [Python Exceptions: An Introduction](https://realpython.com/python-exceptions/)

* Some good information (e.g. `for` loops are built on exceptions! what!) and clarified my thinking somewhat, but not exactly a tutorial: [Write Cleaner Python: Use Exceptions](https://jeffknupp.com/blog/2013/02/06/write-cleaner-python-use-exceptions/)

* His examples are in Ruby, and his writing uses gendered language, but this is otherwise a fairly readable description of when exceptions are most appropriate, in general (rather than in Python):
[Coding Hell's How and When (Not) to Use Exceptions](http://www.codinghell.ch/blog/2013/03/31/how-and-when-not-to-use-exceptions/)

* Apparently I'm into Jeff Knupp's explanations of these things, so here's his article on [The With Statement and Context Managers](https://jeffknupp.com/blog/2016/03/07/improve-your-python-the-with-statement-and-context-managers/)

* Obviously, chapter 33 of Lutz's _Learning Python_, as mentioned in the assignment 😁
