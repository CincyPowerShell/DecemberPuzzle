# DecemberPuzzle

http://powershell.org/wp/2015/12/05/december-2015-scripting-games-puzzle/

The 12 Days of PowerShell! It is that time of year again. Time to think about sugar plums, nutcrackers and PowerShell. Well, maybe we think about that last one all year long. Because I am a giving kind of guy, I thought I‘d give you a PowerShell present. I like to think my present is one that continues to give as it involves learning. I have a small set of challenges that shouldn’t be too difficult, should be fun and in the end educational.

In PowerShell, and I think the ISE might work best for this, create a here string using the attached script.

The variable $list is technically a single string with a length of 226. Using $list, see if you can solve these questions or challenges. I have written these in such a way that the solutions build on earlier answers.

Split $list into a collection of entries, as you typed them, and sort the results by length. As a bonus, see if you can sort the length without the number.
Turn each line into a custom object with a properties for Count and Item.
Using your custom objects, what is the total number of all bird-related items?
What is the total count of all items?
For those of you who have been extra good this year, I have a bonus challenge (or maybe you’ll think it is a lump of coal). Some people interpret The 12 Days of Christmas cumulatively. That is, on day 1 your true love got 1 item. On the second day, your true love got 2 turtle doves AND a partridge in a pair tree. This is in addition to the previous day’s presents. If you were to manually plot this in PowerShell you might do:

4 Lines

$t = 0
$t += 1
$t += 1+2
$t += 1+2+3

But you should be more elegant. Using PowerShell what is the total number of cumulative gifts?
