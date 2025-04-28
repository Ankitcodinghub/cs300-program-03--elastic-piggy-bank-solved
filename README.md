# cs300-program-03--elastic-piggy-bank-solved
**TO GET THIS SOLUTION VISIT:** [CS300 Program 03- Elastic Piggy Bank Solved](https://www.ankitcodinghub.com/product/cs300-p03-elastic-piggy-bank-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117785&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS300 Program 03- Elastic Piggy Bank Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Overview and Learning Objectives:

This time, you’ll be coding up an expandable Piggy Bank (though not infinitely expandable) with much of the same functionality as your first programming assignment.

Grading Rubric:

5 points Pre-Assignment Quiz: You should not have access to this write-up until after you have completed the corresponding pre-assignment quiz through Canvas.

20 points Immediate Automated Tests: Upon submission of your assignment to Gradescope, you will receive feedback from automated grading tests about whether specific parts of your submission conform to this write-up specification. If these tests detect problems in your code, they will attempt to give you some feedback about the kind of defect that they noticed. Note that passing all of these tests does NOT mean your program is correct. To become more confident in this, you must write and run additional tests of your own.

15 points Supplemental Automated Tests: When your final grade feedback appears on

Gradescope, it will include the feedback from these additional automated grading tests. These tests are similar to the Immediate Automated Tests, but check your code against different requirements within this specification.

10 points Manual Grading Feedback: We will focus on looking at your algorithms, use of programming constructs, and the style and readability of your code. This grading usually takes about a week, after which you will find feedback on Gradescope.

Additional Assignment Requirements:

Ensure that your code is styled in conformance with the Course Style Guide.

0. Project Files and Setup

Create a new Java Project in Eclipse called P03 Elastic Piggy Bank. Then create three Java classes within that project’s src folder:

● ElasticBank

● Coin

● ElasticTester

The only class which should have a main method is the tester class. ElasticBank and Coin will be instantiable classes.

1. Creating First Instantiable Class

To keep things simple, begin with the Coin class. Coins have two identifying features: a string representing their name and an integer value representing their worth. Your Coin class should look like this:

● name — String, private

● value — int, private

● public Coin(String name, int value)

● public String getName()

● public int getValue()

And that’s it! Once a Coin has been created, its name and value will not change, so we do not need to define mutators, only accessors. Don’t make these fields final, just private.

The constructor should expect two arguments: a String representing the name of the coin, and a positive integer representing the value. You can assume that the arguments will be valid, and just create the Coin without further checks and toss it to your Witcher.

2. Testing First Instantiable Class

In your ElasticTester, write a test function that creates two (2) coins of different names and values (for example, a penny and a quarter). Test your accessor functions on both coins!

public static boolean testCoinInstantiableClass () {

Coin penny = new Coin(“PENNY”, 1); Coin quarter = new Coin(“QUARTER”, 25); if (!penny.getName().equals(“PENNY”)) return false; if (penny.getValue() != 1) return false; if (!quarter.getName().equals(“QUARTER”)) return false; if (quarter.getValue() != 25) return false; return true;

}

3. Creating Second Instantiable Class

The ElasticBank is similar to your Piggy Bank from P01, but with an important twist: its capacity can expand TWICE before it is “full”.

ElasticBanks have the following private members:

● coins — array of Coins, private

● size — int, private

● expansionsLeft — int, private

● rand — Random, private, static (for use in the removeCoin() method)

Initialize the Random object right away, with whatever seed value you like.

ElasticBank will have two constructors:

● public ElasticBank()

● public ElasticBank(int initialCapacity)

The accessor methods for ElasticBank are:

● public int capacity() — returns the current capacity of the coins array (that is, how many total coins COULD fit in it right now, not including any future expansions)

● public int getExpansions() — returns the number of expansions left

● public int getSize() — returns the current number of Coins in the ElasticBank

● public int getBalance() — returns the current total value of coins in the ElasticBank

● public String getCoins() — returns a String representation of the Coins in the bank (see below):

Because arrays can be modified if a reference is returned, your accessor method for coins should create and return a String representation of the contents of the bank. Each Coin should be represented as “(name, value)”, and the string representation should contain all of these pairs in one space-separated line. For example:

“(PENNY, 1) (QUARTER, 25) (PENNY, 1) (DIME, 10) (NICKEL, 5)”

The mutator methods for ElasticBank are:

● public Coin removeCoin() — removes a Coin from coins at random and returns it, replacing it with a null reference in the coins array.

● public void empty() — empties the ElasticBank entirely, replacing all Coins in coins with null.

● public void addCoin(Coin c) — adds a Coin to the bank and adjusts the capacity of coins if necessary and possible

The removeCoin() and empty() methods should work as they did in P01.

When the ElasticBank’s coins array still has empty spaces, addCoin() works as in P01. When it is full, however, instead of failing as before, create a new array with 10 additional spaces, copy the contents of the previous array over, and add the new Coin. Be sure to decrement expansionsLeft; this operation should only be allowed to happen 2 times during the life of the ElasticBank.

If you try it a third time (that is, when expansionsLeft is 0), the ElasticBank will burst! Use your empty() method to simulate the coins spilling everywhere. After this occurs, go ahead and add that Coin to the now-empty ElasticBank. To be clear:

● If you addCoin() and there is room in the ElasticBank, add the Coin.

● If you addCoin() and the ElasticBank is full:

○ If there are expansions left, expand the bank by 10 slots and then add the Coin (making sure you decrease the number of expansions left)

○ If there are no expansions left, empty the bank and then add the Coin

(You can add Coins to the empty ElasticBank again afterward, but it will not expand again and will keep spilling if you fill it up. It’s not a great bank.)

4. Testing Second Instantiable Class

As this second class isn’t much different from P01, we’re not going to provide specific tests this time. Refer back to P0 for ideas on testing, and make sure you add additional tests to check the expanding part of addCoin().

Be careful: as when you tested Coin, you will want to make at least 2 different ElasticBank objects, and verify that their values are different. An instantiable class is merely a blueprint, and the objects you create from it should be distinct.

public static boolean testBalanceAccessors () {

ElasticBank one = new ElasticBank(5); ElasticBank two = new ElasticBank(7); one.addCoin(new Coin(“PENNY”, 1)); two.addCoin(new Coin(“NICKEL”, 5)); if (one.getBalance() != 1) return false; if (two.getBalance() != 5) return false; return true;

}

5. Assignment Submission
