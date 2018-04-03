# Tartaglia-s-triangle
Tartaglia's or Pascal's triangle - 18 fun experiments with the Tartaglia's triangle a perl Tk program

* Introduction *

In Italy, the arithmetic triangle is called Tartglia's triangle, because exposed in the "General trattato di numeri et misure" written in 1556 by Niccolò Fontana (1499 ca, Brescia 13 December 1557, Venice), known also as Tartaglia.

In 1512 when the French invaded Brescia, a French soldier sliced Niccolò's jaw and palate with a saber. This made it impossible for Niccolò to speak normally, prompting the nickname "Tartaglia" ("stammerer"), which he adopted.

Known as Pascal's triangle (but Pascal drawn it as right triangle) in many other countries was known by Halayuda, an Indian commentator, in 10th century, studied around 1100 by Omar Khayyam, a Persian mathematician, known in China as early as 1261 and so studied in India, Greece, Iran, China, Germany and Italy before Pascal.

About the program: keep it mind i'm not a mathematician, i was only impressed by the huge amount of things you can see in the triangle and i want to show them.

Many useful things about the tartaglia's triangle are shown using the Experiment Panel, others are enumered at the end of this introduction.

When you click a tale of the triangle it's coordinates and it's numerical value are printed on the output window.

Remember that the first row is 0 and the first column is also 0. The triangle is constructed by summing the values of two adiacent position in row and putting the result, below them, in the middle. The general formula to calculate any given number in the triangle given the coordinate is also known as "n choose k"

               n!
 C(n,k) =  ----------
            k!(n-k)!


where n is the row and k is the position, both counting from 0.



* Experiments Panel *

At the top you have the Properties Configuration: This allows the user to determine and/or display:
 * How many rows to draw
 * A button to display this introduction
 * At what point large numbers should be subtituted with dots (to build the shape of the triangle acceptable)
 * The abilty to enable debug information to be displayed on the screen
 * The size and boldness of both output displays
 * The Help Window
 * The main creation or distruction control

Consider that building a bigger triangle requires bigger calculations: You can draw a 127 (or more) row triangle in few seconds on a modern calculator if you want.
If this is the case consider that the values of any element in rows are cached by the main Perl program, so that following calculation will use cached values with no speed penalty.

The next part is a number of experiments you can do with the aritmetic triangle.
The experiments looks very similar:
 * All have some help associated (button '?')
 * A short description
 * An entry field
 * A color chooser
 * And the colorize/clear buttons


* Other properties of the triangle *

-The triangle is symmetrical.
-Some of the numbers in Tartaglia's triangle correlate to numbers in Lozanic''s triangle
-The only number that appears once is 2.
-All entries in row n are odd if and only if the binary representation of n consists of 1s.
-If p is a prime, then every internal entry in row p ^ n (with n as any positive integer) is divisible by p.



* Further readings and credits *

This software is written in Perl and would not be possible without the aid of the community of www.perlmonks.org (just plagiarized some bit from crazyinsomniac, Anonymous, helped by ambrus and wjw and many others).

If you want learn even more properties of the Tartaglia's triangle (seems impossible but there are more) consider worth a visit to:

http://mathforum.org/mathimages/index.php/Pascal%27s_triangle
http://www.cut-the-knot.org/arithmetic/combinatorics/PascalTriangleProperties.shtml
http://ptri1.tripod.com/
http://www.mathsisfun.com/pascals-triangle.html
http://mathworld.wolfram.com/PascalsTriangle.html

