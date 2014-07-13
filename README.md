(in the spirit of
 [https://github.com/samsquire/ideas](https://github.com/samsquire/ideas).)

various ideas and projects
==

these are ideas i'd like to work on, or just things i'd like to see done. if
you complete one of these things, or know some similar software, feel free to
fork and update and issue a pull request!


# incomplete

  1. **movie plot characterisation by graphs**

    this could tell you how complicated the plot is by how many nodes in the
    graph, and so on.

  1. **rotated vim screen based on head position**

    it could adjust text heights to make it appear as if you were always staring
    at it head-on. 

  1. **the inequaliser**

    takes some given equation and considers all the possible inequalities they
    could be used on it.

  1. **programming art workshopy thing**

    a place where you can go and sit and program or do art or whatever. like a
    library. would be a large open space.

  1. ***do*-calculus in networkx**

    implement Judea Pearls *do*-calculus in networkx.

  1. **mathematical property browser**

    suppose you have some object; you'd like to find out what you can do with
    it. for example, you might have a 'simple function'. then it could be
    measureable, say, in the context of measure theory, and so on.

    can generalise to finding various theorems (and lemmas, etc) that could be
    used in certain scenarios. should be easy to use; not at the level of
    proof assistants.

    things like this:
    - [http://slugmath.ucsc.edu/mediawiki/index.php/Main_Page](http://slugmath.ucsc.edu/mediawiki/index.php/Main_Page)
    - [http://www.dougengelbart.org/about/dke.html](http://www.dougengelbart.org/about/dke.html)
    - [http://us.metamath.org/mpegif/mmset.html](http://us.metamath.org/mpegif/mmset.html)

  1. **ambient sound interpreter**

    takes input from the local radio waves, converts them into sound via some
    pattern matching radom strategy. it should be possible to modify, based on
    mood, but it should also sound sufficiently unique as to be interesting.

  1. **stay up to date with specific authors**

    There are a couple of things to do this already.
    * [scirate](http://www.scirate.com/)
    * [google scholar alerts](http://scholar.google.com.au/)

    I also wrote [arxiv-checker](http://arxiv-checker.herokuapp.com/). I'm not
    sure if any of these is perfect, though. arxiv-checker is limited in only
    checking arxiv, and also in the number of people and at the moment only
    does a month back in time. google scholar occasionally gets it wrong (i
    get sent alerts when the author didn't actually publish the paper), and 
    scirate requires you see the paper pop up.

  1. **note from self**

    a thing which reads your comments for 'note to self' and then randomly
    tells you about these things.

    by 'comments' i mean any comment anywhere. for example, this app could
    exist as a skype bot, that joins in on your skype conversations; or
    alternatively it might go through all your source code, or wherever you
    write these things.

    i think it might be best if it responds back in a few ways; i was thinking
    that it could randomly send a message to your terminal, or again with the
    skype thing, it could randomly send you a message.

  1. **lift reading/writing**

    all lifts could contain fixed whiteboard markers; then you could write on
    them if you wanted.

  1. **creative idea generator**

    it should be possible to have a program that generates creative ideas on a
    given topic. as a first pass it should be able to generate other
    'random-combination' based ideas that i've thought of; much like the 'lift
    reading/writing' above.

  1. **programmers keyboard**

    there are many ideas like this, but i'm not sure which one i like best. a
    custom key layout? an actual physical keyboard? a supplemental keyboard to
    the typical one? a modal keyboard?

    one idea is to add a new row of keys. This new row would feature specific
    keys for characters such as: ! ? * < > ( ) { } . " : + & | .

    This list could possible be configured for different languages, as some
    wouldn't require those characters, and may want different ones (for
    example Python, or some form of assembly).

    But at least it may save us from constantly pressing shift, and it may be
    interesting to see if it can lead to other possible benefits; i.e. what
    other buttons could be implemented and considered. It may be interesting
    to consider a 'build' button, or attach some macros to 'programmable'
    buttons. It is already known that [programmable](http://www.artlebedev.com/everything/optimus/) 
    keyboards exist, so maybe they are the answer; but they are very
    expensive.

    maybe this can all be solved by vim configurations, though (as with many
    of lifes problems).


  1. **invalid premise detector**

    imagine if it were possible to look at natural language statements and
    determine an incorrect premise, and have it pointed out. currently it's
    not feasible least-of-all because it isn't possible to programmatically
    review all statements.

    but suppose it were (whether or not this is a good idea, it's becoming
    more feasible), then it would be possible to consider the existence of
    such a program.

    it would look at each statement, and decide whether or not it is
    justified. for example:

    s1: "it doesn't hurt to let people know about standard thing when
    something new comes along"

    could be analysed as invalid, because perhaps it _is_ bad, if say the
    standard things are bad, or similar. i.e. the above statement is only
    valid with certain assumptions.

    perhaps alternatively this project could be something like 'assumptions
    identifier'; and for each statement it is able to work out the assumptions
    under which it is valid.

  1. **programming gallery**

    like an art gallery; but would have particularly nice code examples in it.


  1. **agree-o-tron**

    plugin for skype calls, or similar, that instead of videos just captures
    "agreement", and indicates as much with a pointer. it determines agreement
    by processing video, locally, and then sending only what it infers as
    nodding or disagreeing over the server.

    would need to be a program that runs independently, perhaps, of skype on
    the local machine. then sets itself up as a server for the video stream
    that it is watching; then other people could browse that to get a general
    idea of the "agreement" in that room.


  1. **meeting/discussion emulator**
     
    a system into which you could place people, and list their standard opinions and
    responses, and then model how they will interact with another group of people. it
    could be used to emulate meetings. supposing it emulates meetings well, it could
    then be used to randomly replace meetings in a given company, thus allowing more
    time for whatever people normally do.
        

  1. **encryptoboard**

    a USB device that sits inbetween the keyboard and the computer that outputs
    everything pressed on the keyboard passed through some encryption function. Could
    be a OTP, or something where there are keys involved.


  1. **futuristic restaurant**

    futuristic-themed restaurant, instead of a classic one.


  1. **author hash function**

    calculate a useful hash function that can be queried for closeness when
    related authors publish stuff together. If it funtions like f(A+B) =
    f(B+A) then first-authorship no-longer matters.

    a suggestion is a hash function on a metric space that is also a metric.
    then the idea is to look at the p-adic's and some homomorphism.


  1. **LaTeX typo finder**

    try and find mistakes and whatnot in LaTeX documents by showing only one
    paragraph or sentence at a time. could work with the idea of trying to
    find definitions for all terms, etc.
  

  1. **encouragement bot**

    every time you press enter in your terminal there could be a small chance
    that encouragement bot would say something encouraging.


  1. **some machine learning thing for paper discovery in scirate**

    maybe drafatable are already doing this? if not, consider it.


  1. **a computer proof system that explains WHY things are true**

    in a human-readable way.


  1. **interactive thesis**

    write it in a mathematica notebook or an IPython thing; then I can read
    and interact wtih it. I might do this for part of Belovs thesis, say.

    this, of course, could also be applied to 'interactive papers' at large.
    maybe just as a supplement to any actual paper.

  1. **console chat**

    have a box on a personal website where it says if you're online or not
    (where "online" means "recently used the linux terminal on some
     computer"). if so, people can type a short message to you, which appears
    as say a notify-send. you can then respond to them.)


  1. **a nice local bibtex browser/editor**

    to say replace my current usage of JabRef with. what I'm missing is:
        - ???


  1. **show py.test unit test numbers next to output of tree**

    would prefer to do this with appropriate usage of awk, but i don't know it
    will enough to do that.


  1. **a reusable printing system**

    i want to be able to print pdfs and so on on paper. but i'd also like to
    re-use that paper. naive idea: imagine if we could print in "pencil"
    instead of ink. then i could just rub it out and print again. suppose this
    erasing was handled by the printer though.

    are there ideas like this out there? can i build this myself? review and
    comment.


  1. **a program that splits any given file into ones and zeroes***

    and you can send them seperately, then recreate the original file this
    way.


  1. **post-quantum-cryptography in idris**

    see [http://pqcrypto.org/](http://pqcrypto.org/).


  1. **some sort of self-organised university thing**

    where you could declare a set of subjects you will run, and layout some
    course plan, and then teach yourself those things. the idea would be to
    just have some structure and way of remembering what you should be doing,
    and accountability.

    for some reason it seems fun to perhaps use gitit for this.


  1.  **calculate number of mistakes one can make**

    none is bad. two is also a bit arbitrary. it's probably a function of the
    'class' of mistake, and whether or not you claim to know how to not make
    that mistake again, etc. try and calculate what this is.


  1. **a file-system rpg**

    it should lay out a particular directory structure as a big rpg land that
    you must explore. files that you want to delete become enemies.


  1. **programming language heatmap**

    a plugin for vim/emacs that tracks the time spent programming in particular
    languages. could match this to physical location (gps?) and then generate
    a heatmap that way. maybe some of this information is already on github.


  1. **a reasoning layer**

    for programming languages. in reference to being able to deduce how
    computers decided on a particular course of action. in python this could
    be implemented with decorations on functions which categorise the
    function, and then take this coarse-grained categorisations and map them
    into functional sections somehow. i.e. group them in some meaningful way.
    output as a graph or something.


  1. **rich hickey talk generator**

    find words used in programming, define them, note disparity with common
    usage, comment.

    - [value of values](http://www.infoq.com/presentations/Value-Values)
    - [simple made easy](http://www.infoq.com/presentations/Simple-Made-Easy)


  1. **a robot whose goal is to be happy and have fun**

    instead of doing something "useful" it could just aim to have the most fun
    possible.

    - see for example [dancing japanese robot](https://www.youtube.com/watch?v=3g-yrjh58ms)
    - [keepon beatbots](http://beatbots.net/)

    
  1. **program to generate dance moves**

    further to the above; could display them to the public and let them vote,
    etc.

  
  1. **tested-by**

    finds the unit tests that a given file is tested by. can be used to run
    the tests automatically when the file changes.

 
  1. **quadmule**

    suppose you have something to take somewhere but don't want to carry it.
    you could use a qaudcopter to fly it along with you. for example, i want
    to run home but don't want to carry my bag. i guess a robot would also
    work, but you'd have to walk with it. the quadcopter could just follow you
    in the air.


# complete

  1. **laptop whiteboard**

    a whiteboard attached to your laptop.

    ![laptopwhiteboard1](resources/laptop-whiteboard1.jpg)
    ![laptopwhiteboard2](resources/laptop-whiteboard2.jpg)

    you require only melamine, or some similar material, and velcro dots.
    pictured is some transparency paper stuck on a piece of corregated
    plastic. i've found the melamine purchased from a shop tends to not clean
    as nicely as the whiteboards you find at universities; i'm not sure why.
    recommend using these with the thin-tipped whiteboard markers.


  1. **australian budget tracker**

    somehow find out how the tax money is spent in australia, and do some sort
    of modelling on it.

    basically exists, but probably needs a bit more work:
    - [http://infoaus.net/budget/budget_home.php](http://infoaus.net/budget/budget_home.php)


  1. **what-now**

    looks at your timetable, and tells you what you should be doing now. will
    need to configure a timetable in some trivial json format.

    basically exists:
    - [http://taskwarrior.org](http://taskwarrior.org)

    (that is, I now use taskwarrior for this purpose.)


  1. **this file upsets me**

    you can upload the sha256 hash of a file, and then the system counts that
    file as upsetting n+1 people. list the topmost upsetting file hashes.
    never reveal the actual file contents.

    might change this to be 'how i feel about this file', and you can love it,
    or have it upset you.

    done:
    - [http://this-file-me.meteor.com](http://this-file-me.meteor.com)


  1. **git console dashboard**

    at a glance i'd like to see the status of all my repos; the
    outgoing/incoming changes from various upstream sources, etc; then i could
    issue system-wide updates and so on.

    there appear to be a few things like this, but are gui-based.

    done:
     - [Some tools for working with Github upstream repos](http://silky.github.io/posts/2014-06-21-some-tools-for-working-with-github-upstream-repos.html)
