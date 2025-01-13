# Warframe App with `.NET8.0 WASM` + `Blazorise/BootstrapV5`

Before I get to talk about the webapp itself, I will firstly talk about the background for this game

## Background

In the age of information, certain applications and data is considered paramount. When discussing games (*Mainly Online games*) certain ideas might pop in to ones head. For me it is always, how does one most efficiently play this game if I choose to play it a lot?

This is where certain criteria come into play:
1. The grind of the game
2. The playstyle of the game
3. The expectations of the game
4. The amount of content within the game

Notice that only one of the four points actually deals with the game content. The rest is what a player deals with while doing the content of the game.

**Warframe** is probably the greatest game ever made. It is free-to-play, the game mechanics is godly, the amount of contents is never ending (*Especially now that Rebecca has a finger in play*) and the game never put any expectations on the player to use money on it. The last bit has to be highlighted. Never in my life have I ever met a free online game where I want to give the developers (**DE**) money. And this is the voice echoed by the community. Yes, there is still "premium" features within the game but they aren't needed as long as you are willing to just put some hours in to the game. The most egregious case of this is their building delays. To build a warframe you will normally need 1 resource and 3 warframe part. The resource is generally easy to get and the warframe parts is also normally considered to be easy to get. Each warframe part will also need to be built from resources, either some generic resources or some content update specific ones.

The parts take 24 hours each (*can be built in parallel*) and the warframe takes 72 hours. This means for a end-user not willing to use platinum (*their premium currency*) they would have to wait minimum 96 hours before they can enjoy their new content. Rebecca has said that they are willing to look and change this for future content and maybe even past content.

### The optimisation of gameplay

If we look past the small part of the game that is considered the worst, then the game has a lot to offer. The mechanic of the gameplay can take hundreds of hours to master, there is no expectation from the developers to rush to the end game (*specifically they are saying that*) and more importantly there exists different levels of grinding that can both be short and long.

To deal with the grinding one can either go with *The-Old-Reliable* build or have an efficient build for almost all occasions. So let us look at how many different builds we can have in warframe only looking at warframes, primary weapons, secondary weapons and melee weapons (No modular weapons) as of the time writing this (*Update 38*) .

> **Warframes:** Total of 104 (*105 with `Excaliber Prime`*)  
> **Primary Weapons:** 176 total  
> **Secondary Weapons:** 136 total (*137 with `Lato Prime`*)  
> **Melee Weapons:** 204 total  (*205 with `Skana Prime`*)  

This list excludes the modular weapons and also any companion/archwing/necremech a person desire to have. So if we were to only look at these without the founders primes, we would look at the following amount of combinations:
$$
\texttt{Amount of combinations}=104\cdot176\cdot136\cdot204=507.826.176
$$
Assuming that a simple exterminate mission takes 3 minutes that would mean a player would have to play $1523478528$ minutes or roughly $2896.5$ years without stopping and with no time taken between missions. Clearly this is ridicolus and nobody would ever be expected to do that. Mostly people stick to a couple of warframes and some weapons. The rest is just "*mr-fodder*" (*just used to level up mastery rank*).

So how do we decide what we shall use for actual game play and what we shall just level up and then never use again? This is where the optimization problem play a hand. Nobody could reliable makes this decision alone. Some weapons might work with some warframe, but to know that, one would have to play that combination and then we are back at the over 2000+ years of playtime. Instead we need to rely on each other and `DE`.