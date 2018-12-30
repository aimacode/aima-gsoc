# Project Ideas for `aimacode`


We are looking for students to work on `aimacode` for the [Google Summer of Code](https://summerofcode.withgoogle.com) (GSoC) in 2018. We don't know for sure how many students we will be allowed to sponsor, but here are some project ideas:

## Project 1: Finish `aima-python` algorithms and add explanatory notebooks

Finish the implementation of the [pseudocode](https://github.com/aimacode/aima-pseudocode) algorithms in Python: we have [a list](https://github.com/aimacode/aima-python/blob/master/README.md) of half a dozen algorithms yet to implement, and a dozen still requiring tests. For this we're looking for coders with good taste: the code needs to work, of course, but it also needs to be easy for the reader to understand, and to have a very close (almost one-to-one) correspondence to the pseudocode in the book.

In addition to that, we would like to add ipython (jupyter) notebooks that explain how to use the algorithms, and show their application to specific domains, demonstrating both how to use the code, and how the underlying AI ideas work. The notebooks should also inspire the reader to try out new ideas of their own. This requires coding skills, but also English writing skill and good educational pedagogy. Potential mentors: Dragomir Radev, `dragomir.radev@yale.edu`, and
Pierre de Lacaze, `raymond.delacaze@gmail.com`.

## Project 2: Finish `aima-java` algorithms

Finish the implementation of the [pseudocode](https://github.com/aimacode/aima-pseudocode) algorithms in Java: we maintain a [list](https://github.com/aimacode/aima-java#index-of-implemented-algorithms) of algorithms that are currently implemented in the repository or need to be implemented.

Most of the algorithms from the third edition have been implemented. Currently, the authors are working on the __fourth edition__ of the text. The algorithms from the fourth edition are updated simultaneously in the [pseudocode](https://github.com/aimacode/aima-pseudocode) repository. These algorithms are required to be updated in the AIMA4e branch of the repository. As far as the third edition is concerned, we have introduced __Java-Notebooks__ so that it becomes easier to experiment with the code in the __browser itself__. Following are a few lines along which you can initiate your work:

1. Most of the algorithms from the third edition are complete. However, the __testing suites__ have a large scope of improvement. You can begin by writing __test cases__ for any of the algorithms. It is also the best way to take a grasp of the codebase.
2. Since the notebooks were introduced only in the last year, there are very few [completed notebooks](https://github.com/aimacode/aima-java/tree/AIMA3e/notebooks). You can begin by picking up a chapter of your choice and then exploring them in the notebooks.
3. You can keep an eye on the [pseudocode](https://github.com/aimacode/aima-pseudocode) repository and implement any new algorithms introduced for the fourth edition in the AIMA-4e branch. You can further visit [this](https://github.com/aimacode/aima-java/issues/438) issue for inspiration.

The code needs to work, of course, but it also needs to be easy for the reader to understand, and to have a reasonably close correspondence to the pseudocode in the book. Potential mentor: Peter Norvig `peter@norvig.com`.

## Project 3: Graphical demos in `aima-javascript`

Here we're not interested in showing Javascript code that implements algorithms, but rather in having interactive graphical demonstrations ([example](http://aimacode.github.io/aima-javascript/3-Solving-Problems-By-Searching/)): we have a [list](https://github.com/aimacode/aima-javascript/wiki/How-to-Contribute) of algorithms yet to be implemented. So this project is for someone who can write Javascript, but more importantly someone with good graphic design sense, and an ability to invent good educational material. An example of the type of animation I'd like to see is the [A* tutorial](https://www.redblobgames.com/pathfinding/a-star/introduction.html) at Red Blob Games. Potential mentor: Sam Goto, `goto@google.com`. See [the guide to applying](https://github.com/aimacode/aima-javascript/wiki/GSOC-2018).

## Project 4: Initiate `aima-exercises`

This is a new project: build a website (on GitHub) for the exercises that were in the AIMA book for the third edition, but will be only online in the fourth edition. We currently have LaTeX source for the exercises. We need to reorganize as follows:

- Translate the current exercises from LaTeX into markdown (this may be done before GSoC starts).
- Design a good format to display the exercises as pretty [GitHub pages](https://pages.github.com/).
- Create some new, high-quality exercises, with solutions. Concentrate on exercises that require programming solutions.
Your sample solutions have to not only solve the problem but also clearly demonstrate the concepts to the students.
- Create an encouraging community for volunteers to write new exercises and solutions and correct/augment old ones.
- Design a system where students can vote/rank exercises.
- Figure out a way to have the answers for some exercises hidden (so that professors can assign them as homework) and have the answers for others (and discussion forums) available for the community.

Potential mentor: Peter Norvig `peter@norvig.com`.


# Your Application

If you are interested in applying as a GSoC student, you should:
- Say which of the above areas you are interested in working on.
- Say what your experience is, including pointers to some projects you've worked on.
- Bonus points if you've contributed to `aimacode` already: look for an open issue and pitch in; let us know what you've done in the application.
- You don't need a detailed proposal saying what specific things you want to do within an area--just general areas you are interested in.
