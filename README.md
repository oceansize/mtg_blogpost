As a Coach at Makers Academy, I'm often asked how to improve your programming skills - and there are indeed many ways. Some seem extremely logical (practice lots, use a [REPL](http://pryrepl.org/), do some code katas, start reading the docs). Others, a little more left-field (try meditation, do some yoga, utilise the pomodoro technique)...

But the suggestion that raises by far the most eyebrows is when I tell students to **play [Magic: The Gathering](http://magic.wizards.com/).**

### WTF is Magic: The Gathering?

For the uninitiated, Magic: The Gathering (often referred to as 'Magic' or 'M:TG') is a card game released in 1993, which is heavily steeped in fantasy imagery and lore, and pits two players in a strategic battle to reduce their opponent's given life total to zero. There is a fantastic video [here](https://www.youtube.com/watch?v=LbnfSG_WGXI), which takes you through the rules, using the videogame for visual emphasis.

Many of the cards have become collector's items, and while $10,000 for one card might seem insane, there are regular pro tours which can yield up to $40,000 for the winner (with a total of $250,000 being paid out by the competition overall). Make no mistake, Magic is big business, with tens of millions of players worldwide, and has spawned an entire industry filled with card expansion packs, videogames and thousands of accessories.

### Isn't that for Nerds though?

In a word, no. I know what you're thinking - this is the part where the nerd desperately tries to convince you that he's actually really cool, and you should join him etc. But I don't want you to learn how to play Magic. You'll just drive up demand for all the good cards, all the spots for pre-release events will be harder for me to get, and frankly I like having niche interests, like bands you've never heard of. I'm only writing this because my boss wants me to justify why we play so much Magic at work. Sure, it takes some effort to get through the lore and the rules text if, like me, you're not big into fantasy: even Ryan Gosling would struggle to utter "Loxodon Smiter deals 4 damage to your Planeswalker" and still feel attractive... But if you can put your vanity aside for twenty minutes, you are entering into a world of beautiful and complex mechanics that will bring you delight, frustration, intrique, crushing defeat, sweeping victory and ultimately fun beyond measure. It also helps you think.

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

Now, if you were going to play 'Biting Rain', it's important to read the wording, because **"All creatures"** mean _your_ creatures too. An easy thing to miss when you're in an attack mindset, and a mistake that could wipe out many of your creatures and actually do your opponent a favour.


### Mental Modelling

A large part of learning to code is getting your brain into the habit of holding a lot of moving parts in memory at once: variables containing shifting values, objects mutating state and collaborating with other objects, callbacks waiting to be triggered and promises waiting to be returned. When you are programming, you are asking a lot of your mind - and Magic gives you excellent opportunities to practice this. Consider the card 'Triskaidekaphobia':

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=409891&type=card)

>
At the beginning of your upkeep, choose one —  
• Each player with exactly 13 life loses the game, then each player gains 1 life.  
• Each player with exactly 13 life loses the game, then each player loses 1 life.

This card allows you to defeat your opponent by reducing their life total to _exactly 13_ instead of _0 or less_. But it takes planning on both sides. Each player needs to keep a mental tally of all the cards out on the table, and constantly remind themselves of all the possible outcomes of each card being played/removed. Which you should be doing anyway, but 'the trike' really sharpens the mind.

Once you've played 'Triskaidekaphobia', you must plan you attacks so that you can get your opponent down to 13 life at exactly the right point (the ability checks for 13 life at the beginning of each of your turns) whilst keeping your own life total within a safe range - for your opponent, they must be mindful that this card is in play, and avoid the number 13 at all costs ([hence the title of the card](https://en.wikipedia.org/wiki/Triskaidekaphobia)).

Understanding the knock-on effects of each method/function in your code is essential for programming success, and we find at Makers Academy that the more you do it, the better you get. Magic: The Gathering offers you a fun way to build this practice away from the computer.

Magic is a turn-based game, and each turn has several phases, where different cards can be played and various actions or effects can occur. If you're really paying attention, you can even hijack certain parts of your opponent's turn to your own advantage. This sequencing is a great way to help train yourself to stay on top of various stages of execution in your code. Super useful when you start working with 3rd party APIs and have to figure out where all your data is going!

### Pattern Recognition

Experienced developers often talk about 'the shape of the code' and are able to see 'patterns' that start to crop up again and again when working on software. This ability to recognise sequences that repeat is a big factor in being able to measure your experience level (and salary expectations). When it comes to Magic, you will frequently see card combinations crop up, notice behaviours of your opponent which will allow you to predict the move they are building up to, and even recognise complimentary abilities between cards which may require you to switch cards out of your deck between matches (a practice called 'Sideboarding').

### Deck Building

_WILL - I think deck building is actually the closest thing to programming. You can then lead into Goldfishing as QA._

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

Believe it or not, Magic employs the very same device whenever someone 'casts a spell' (plays a card). Ordinary people struggle with this concept - but not you. I have faith in you.

Let's say we have a [Kalonian Tusker](http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=370700) ready to attack:

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=370700&type=card)

> No special ability, just 3 power, 3 toughness.

Now let's say you're using it to attack your opponent for 3 damage (the Tusker's 3 power deals 3 damage, which causes your opponent to lose 3 life).

Just before this beast takes a chunk out of your opponent, they have a last-minute chance to cast spells.

Your wiley opponent has chosen [Fiery Temper](http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=409908) and selects your Tusker as the recipient of the 3 damage:

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=409908&type=card)

> Fiery Temper deals 3 damage to target creature or player.

The Fiery Temper goes on the Stack - which is like a holding pen for things that are about to happen - and you now have the opportunity to respond to your opponent's spellslinging. If you don't, the Fiery Temper will kill your Tusker.

So, on top of your opponent's card, you place [Rush of Adrenaline](http://gatherer.wizards.com/Pages/Card/Details.aspx?multiverseid=409932):

![](http://gatherer.wizards.com/Handlers/Image.ashx?multiverseid=409932&type=card)

> Target creature gets +2/+1 and gains trample until end of turn.

Our stack looks like this:

|                    |
|--------------------|
| Rush of Adrenaline (target: Kalonian Tusker) |
| Fiery Temper (target: Kalonian Tusker) |

1. Rush of Adrenaline gets popped, and increases the power and toughness of the Kalonian Tusker from 3/3 to 5/4; then
2. Fiery Temper gets popped, and deals 3 damage to the Kalonian Tusker - but it's now got 4 toughness, so it survives.

Let's look at that the other way around: what if your opponent has just 5 life remaining, so you decide to use your Rush of Adrenaline to finish the game (by pumping your Tusker to 5 power)?

So now the Rush of Adrenaline goes on the Stack first - but then your opponent responds with the Fiery Temper - so our Stack looks like this:

|                    |
|--------------------|
| Fiery Temper (target: Kalonian Tusker) |
| Rush of Adrenaline (target: Kalonian Tusker) |

So now, the sequence of event goes like this:  
1. The Fiery Temper (because it's on the top of the Stack) gets popped first - dealing 3 damage to your Kalonian Tusker and killing it, deady dead dead;  
2. The Rush of Adrenaline is pointed at a creature that no longer exists, so nothing happens - it 'fizzles'.  

So, casting one spell before another coudl be the difference between life and death. Not literally, of course.

If that was a bit tricky to get your head around - don't worry! You just need to play more Magic, and do more coding! Luckily we do both here at Makers Academy...

### Conclusion

Magic is awesome, and a great way to unwind with friends and colleagues after a hard day's coding. It's a lot more mentally stimulating than watching TV (unless it's streaming [Sandi Metz talking at RubyConf...](https://www.youtube.com/watch?v=URSWYvyc42M)) and I believe it geniunely helps people exercise the same cognitive processes that benefit programmers. Plus if you're worried about being labelled as a 'Mage' or 'Paladin', don't be - there are many sets of cards with different themes ranging from Victorian horror to Shaolin monks. 
