Download Link: https://assignmentchef.com/product/solved-prolog-assignment3-accumulator-negation-input-output-functor
<br>



Write PROLOG programs for 1-5.

<ol>

 <li>To find factorial N using accumulator.</li>

 <li>To find length of a list using accumulator.</li>

 <li>To remove duplicate elements from a list using accumulator.</li>

 <li>To remove duplicate elements from a list without using accumulator.</li>

 <li>To reverse a list using accumulator.</li>

 <li><strong>Next Higher Permutation</strong>.</li>

</ol>

A positive integer is represented by a list of decimal digits. Its next       higher permutation is defined to be the next greater integer composed of        exactly the same digits. For example, the next higher permutation of       123542 is 124235.

Write a) a declarative Prolog program

<ol>

 <li>b) an efficient procedural Prolog program that receive a list of decimal digits and return its next higher permutation   in a list.</li>

 <li><strong>Eight Queens’ Problem. </strong></li>

</ol>

<strong>           </strong>Eight Queens are to be placed in an 8×8 chess board such that no queen            attack each other.

Write a Prolog program to obtain solution(s) of Eight Queen Problem.

<ol start="8">

 <li><strong>Tower of Hanoi Problem. </strong></li>

</ol>

<strong>           </strong>The tower of Hanoi is a game played with three poles and a set of N discs.            The discs are graded in diameter, and fit onto the poles by means of a            hole cut through the center of each disc. Initially all the discs are on the             left-hand pole. The object of the game is to move all the discs onto the           center pole. The right-hand pole can be used as a “spare” pole, temporary            resting place for discs. Each time a disc is moved from one pole to

another, two constraints must be observed: only the top disc on a pole can            be moved, and no disc may be placed on top of a smaller one.            Write Prolog program to enumerate the moves to transfer N discs from           the left-hand pole to the center pole.

<ol start="9">

 <li>There is an old song that goes as follows:</li>

</ol>

99 bottles of coke on the wall

99 bottles of coke

You take one down and pass it around

98 bottles of coke on the wall    and so on, until the last verse                1 bottle of coke on the wall

1 bottle of coke

You take one down and pass it around                No bottle of coke on the wall.

Write a Prolog program <em>cola</em> that receives a positive integer and prints            the Lyrics of the song. The program should print all the verses, and when            it gets to the last verse, it must print 1 <em>bottle</em>, not 1 bottles and <em>no bottle            </em>rather than 0 bottles.

<ol start="10">

 <li>In a lost-world language, a poem can have any number of verses, each of which takes the following form:</li>

</ol>




A      B      B      C

D      E      E       C

F       F      G

H      I        I        C




where the same letter represents rhymed words. For example,




anun kura tama su                unuri bimo co kuru                sonen ariten sicom                kana te shime xanadu.




Design a database to store a number of lost-world words and write a Prolog    program to produce a poem for a given number of verses.




<ol start="11">

 <li>Three musicians of a multinational band take turns playing solo in a piece of music: each plays only once. The pianist plays first. John plays saxophone plays before the Australian. Mark comes from the United States and plays before the violinist. One soloist comes from Japan and one is Sam.</li>

</ol>

Write a PROLOG program to find out who comes from which country, plays what instrument, and in which order

<ol start="12">

 <li>One way of representing the positive whole numbers is a Prolog terms involving the integer 0 and the successor functor s with one argument. Thus, we represent 0 by itself, 1 by s (0), 2 by s (s (0)) and so on. Write definitions of standard arithmetic operations addition, multiplication and subtraction, given the above representation of numbers. For example, the predicate plus may be defined to exhibit the following behavior.</li>

</ol>

? – plus (s (s (0)), s (s (s (0))), X).

{X= s (s (s (s (s (0)))))} that is, 2+3 = 5. Also define the predicate “less than”, “greater than”, “less than equal to” and “greater than equal to”. Further define arithmetic operations, like integer division, remainder of integer division,  and square root.


