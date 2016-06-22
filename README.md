As a Coach at Makers, I am often asked by people how they can improve their programming skills- and there are indeed many ways. Some seem extremely logical (practice lots, use a [REPL](http://pryrepl.org/), do some code katas, start reading the docs). Others, a little more left-field (try meditation, do some yoga, utilise the pomodoro technique)...

But by far the suggestion that raises the most eyebrows is when I tell students to **play [Magic: The Gathering](http://magic.wizards.com/).**

### WTF is Magic: The Gathering?

For the uninitiated, Magic: The Gathering (often referred to as 'Magic' or 'M:TG') is a card game released in 1993 which is heavily steeped in fantasy and pits two or more players against one-another in a battle to reduce your opponent's given life total to zero. There is a fantastic video [here](https://www.youtube.com/watch?v=LbnfSG_WGXI) which takes you through the rules, using the videogame for visual emphasis.

Many of the cards have become collector's items, and while $10,000 for one card might seem insane, there are regular pro tours which can yield up to $40,000 for the winner (with a total of $250,000 being paid out by the competition overall.) Make no mistake, Magic is big business, and has spawned an entire industry filled with card expansion packs, videogames and thousands of accessories.

### Isn't that for Nerds though?

In a word, no. I know what you're thinking - this is the part where the nerd desperately tries to convince you that he's actually really cool, and you should join him etc. But I don't want you to learn how to play Magic. You'll just drive up demand for all the good cards, all the spots for pre-release events will be harder for me to get, and frankly I like having niche interests, like bands you've never heard of. I'm only writing this because my boss is making me justify why the team play so much Magic. Sure, it takes a bit to get through the lingo if like me, you're not big into fantasy; even Ryan Gosling would struggle to utter "Loxodon Smiter deals 4 damage to your Planeswalker" and still feel attractive... But if you can put your vanity aside for twenty minutes, you are entering into a world of beautiful and complex mechanics that will bring you delight, frustration, intrique, crushing defeat, sweeping victory and ultimately fun beyond measure. It also helps you think, too.

### What has any of this got to do with programming?

So glad you asked. One of the reasons that we see so many of our students developing a nasty Magic habit is the fact that there are some undeniable links between this game, and coding.

### The Great Unknown

Being comfortable with the unknown is an _essential_ part of being a developer. When you're getting started on a new project, or chasing down a bug - chances are you will not know what you are doing (at least at the start of your career.) Someone will ask you to build a feature that sounds impossible - but a great developer will stride into those unfamiliar waters and swim investigatively towards a solution.

On the coaching team we are particularly keen on seeing students develop a [growth mindset](http://mindsetonline.com/thebook/buythebook/index.html) - and part of this is relishing challenge. Another huge factor is being comfortable with failure as a feedback mechanism, as opposed to some sort of permanently defining characteristic of a person's being. Magic helps with this also! Each game starts with a randomly-selected hand of seven cards - and ultimately there is an element of chaos in this that means the game will always keep you on your toes no matter how powerful your deck is.

### Read the Docs

Possibly one of the biggest skills our students learn, is how to interpret documentation for their chosen language/technology and understand what features/limitations are going to affect their day in front of the computer.

Reading and understanding the instructions accurately make a huge difference to how effective you will be as a developer, and Magic really helps you hone that skill, as interpretation of the rules on a Magic card can make the difference between success and defeat. Take for instance this card [Biting Rain](http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=409849):

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=409849&type=card)

Now, the important part is the line:

> "All creatures get -2/-2 until end of turn"

In Magic, creatures have **power** / **toughness**, represented as follows: 4/2. So if a creature was affected by the above line, its power and toughness would be reduced to 2/0 - and when a creature's toughness is reduced to 0 or below, it dies.

Now, if you were going to play 'Biting Rain', it's important to read the wording, because **"All creatures"** mean _your_ creatures too. An easy thing to miss when you're in attack mode, and a mistake that could wipe out many of your creatures and actually do your opponent a favour.


### Mental Modelling

A large part of learning to code is getting your brain into the habit of holding a lot of moving parts in memory at once. Variables containing shifting values, objects mutating state and collaborating with other objects, callbacks waiting to be triggered and promises waiting to be returned. When you are programming, you are asking a lot of your mind - and Magic gives you excellent opportunities to practice this. Consider the card 'Triskaidekaphobia':

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=409891&type=card)

>
At the beginning of your upkeep, choose one —
• Each player with exactly 13 life loses the game, then each player gains 1 life.
• Each player with exactly 13 life loses the game, then each player loses 1 life.

This card allows you to defeat your opponent in one move if they are foolish enough to allow their life total to sit at 13 when you have this card out on the table. But it takes planning on both sides. Each player needs to keep a mental tally of all the cards out on the table, and constantly remind themselves of all the possible outcomes of each card being played/removed.

For the person in control of 'Triskaidekaphobia', they must try and plan their attacks so that they can get their opponent down to 13 points at exactly the right point whilst keeping their own life total within a safe range - for the opponent, they must be mindful that this card is in play, and avoid the number 13 at all costs ([hence the title of the card.](https://en.wikipedia.org/wiki/Triskaidekaphobia))

Understanding the knock-on effects of each method/function in your code is essential for programming success, and we find that the more you do it, the better you get at it. Magic: The Gathering affords you a fun way to build this practice away from the computer.

Magic is a turn-based game, and each turn has several sections, or 'phases' where different cards can be played, and various actions or effects can occur. If you are really paying attention, you can even hijack certain parts of your opponent's turn to your own advantage. This sequencing is a great way to help train yourself to stay on top of various stages of execution in your code. Super useful when you start working with 3rd party APIs and have to figure out where all your data is going!

### Pattern Recognition

Experienced developers often talk about 'the shape of the code', and are able to see 'patterns' that start to crop up again and again when working on software. This ability to recognise sequences that repeat is a big factor in being able to measure your experience level (and salary expectations.) When it comes to Magic, you will frequently see card combinations crop up, notice behaviours of your opponent which will allow you to predict the move they are building up to, and even recognise complimentary abilities between cards which may require you to switch cards out of your deck between matches (a practice called 'Sideboarding'.)

### Test-Driven Fishing

At Makers Academy we are extremely passionate about Test-Driven Development - a practice where you write tests for code, before you write your software. The idea behind this, is that for each piece of code you write, you have some level of assurance that it's producing the kind of behaviour you want to see. In Magic, there is a technique called 'Goldfishing' which is when you play a game against an imaginary opponent, to get a feel for how well you have constructed your deck. This allows you to recalibrate it if you find it's lacking elements, or if you have a little too much of something.

### Not being distracted by the shiny

Far too often as developers we are tempted to choose a sexy new technology just because we _want it_! Look at all the cool things it can do right out of the box! We'd be crazy to pass up on that - right? Wrong. There's a joke that if you can think of a noun, append '.js' to the end of it and there will be a JavaScript framework of the same name.

Many a questionable architecture has been attributed to programmers being seduced by seemingly all-powerful technologies, only to find they were all style and no substance. The same can be said for Magic, and this is particularly evident during the practice of 'Drafting'- where players pass around a randomised selection of cards, taking one each time and agonising over each pick. Should they take the foil-stamped rare card? Or should they instead build a solid foundation for their deck and pick a solid, dependable workhorse?

Check out [Arcane Melee](http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=376246):

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=270993&type=card)

Look at that sweet artwork! The flames! The lightning bolts! Look at the gold symbol on the right that shows this is a RARE card! One of the mechanics of the game, is that you have to 'pay' to bring cards out onto the table, and in the upper right corner, this 'cost' totals to 5 (which is getting on the side of pricey.) But look, it makes other types of card cheaper (by 2) to cast! Surely this is a fantas... No. If you read the wording carefully, this applies to ALL 'instant' and 'sorcery' cards, NOT JUST YOURS. This is about as useful as a chocolate fire engine on a hot day.

But imagine you've just opened a fresh pack of cards, and this is amongst them, printed on [foil and gleaming at your very soul...](http://i.ebayimg.com/images/g/-Q0AAOSwxH1T9fOY/s-l300.jpg) Would you have the self control to put it back on the pile and take an [Elvish Mystic](http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=370744) instead?

Those lightning bolts do look sweet though...

### The Stack

Possibly the most obvious parallel between programming and Magic has to be the concept of 'The Stack'. Essentially, in computer science the stack is a way of keeping track of "the point to which each active subroutine should return control when it finishes executing." OK as a warm up, [go here and click some buttons](https://www.khanacademy.org/computer-programming/stack-visualization/6117875093078016) and that should give you a feel for the 'last in, first out' ordering. Fun eh?

So let's take a simple program in JavaScript:  `1 + 2`. No actually, let's make it LISP instead: `(+ 1 2)`. Crazy huh? Same thing though - promise. Let's imagine that the interpreter goes through this, character by character, and when it hits the closing parenthesis it works its way backwards, placing each character on a pile until it gets back to the beginning. You'd end up with something like this:

|   |
|---|
| + |
| 1 |
| 2 |

Then let's say that the interpreter then starts executing this from top to bottom. First we 'pop' the top element off our stack and realise it's a function that _adds_ two elements together, so we should be expecting to find two elements next.

|   |
|---|
| 1 |
| 2 |

The next item we pop is indeed the number 1, so we're halfway there...

|   |
|---|
| 2 |

Aaaaand the final piece of our puzzle - we pop another number, this time 2. Our stack is empty, and we return the result, which is the number 3!

Believe it or not, Magic employs the very same device in it's combat mechanism. Ordinay people struggle with this concept - but not you. I have faith in you.

Let's say we have a [Kalonian Tusker](http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=370700):

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=370700&type=card)

> No special ability, just 3 power, 3 toughness.

Now let's say you're using it to attack your opponent for 3 points. (They've only got 3 points left, so if you land your blow the game is won!)

Oh no, your opponent responds by placing [Fiery Temper](http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=409908) on top of your card:

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=409908&type=card)

> Fiery Temper deals 3 damage to target creature or player.


We have now formed a stack, and your opponent wants to deal you 3 damage. This is tense, because you only have a **toughness** of 3. Fiery Temper could KILL you! Fortunately, you're made of sterner stuff. On top of your opponent's card you place [Rush of Adrenaline](http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=409932):

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=409932&type=card)

> Target creature gets +2/+1 and gains trample until end of turn.

Our stack looks like this:

|                    |
|--------------------|
| Rush of Adrenaline |
| Fiery Temper       |
| Kalonian Tusker    |

Let's walk it through. Rush of Adrenaline gets popped, and 'Target creature is naturally going to be our Kalonian Tusker, which now has a power and toughness of 5/4 (increased from 3/3).

Our stack now:

|                    |
|--------------------|
| Fiery Temper       |
| Kalonian Tusker    |

Now it's Fiery Temper's time to shine as we pop it off the stack, and watch it deal 3 damage to the Kalonian Tusker.

|                    |
|--------------------|
| Kalonian Tusker    |

This brings the Tusker's toughness down by three, leaving it's final stats as 4/1. Painful, but not enough to kill it, so it deals 4 damage to the opponent (who only had 3 life points left), leaving them with -1 and you win the game!!!

If that was a bit tricky to get your head around - don't worry! You just need to play more Magic, and do more coding! Luckily we do both here at Makers Academy...

### Conclusion

Magic is awesome, and a great way to unwind with your friends and colleagues after a hard day's coding. It's a lot more mentally stimulating than watching TV (unless it's streaming [Sandi Metz talking at RubyConf...](https://www.youtube.com/watch?v=URSWYvyc42M)) and I believe geniunely helps people exercise the same cognitive processes that benefit programmers. Plus if you're worried about being labelled as a 'Mage' or 'Paladin', don't be - there are many sets of cards with different themes ranging from Victorian horror to Shaolin monks.
