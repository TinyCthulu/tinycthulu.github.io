---
layout: post
title:  The Procedural Procedural Pt. I
categories: blog
---

## An exploration into the cursed nature of the procedurally generated detective game.

> In this post, we will explore the cursed nature of the procedurally generated detective game. We will deconstruct some of the more interesting challenges along the way, and by the end, we will have a deeper insight into the problem as a whole.

## **Introduction**

I have always loved procedural police dramas on TV, particularly those involving a clever detective. A well done procedural has a narrative that is bound to draw you in with witty humor, an intriguing mystery, and a juicy twist. My only real problem with the format is actually a problem with the *mystery* genre as a whole.

Once you know the secret twist or solution, the mystery loses it's magic. It can be difficult to re-experience. Don't get me wrong, a clever story with interesting characters and well-written dialogue will stand on its own two feet the first time and the hundredth time. In that sense a classic mystery is no different from any other story. It's why we can still revisit the tales of popular characters like Sir Arthur Conan Doyle's Sherlock Holmes, Agatha Christie's Hercule Poirot, or the infamous Shawn Spencer from the TV show Psych. But, unlike most other *kinds* of stories, the *unknown* plays a disproportionate role in the mystery genre. 

The interesting thing about suspense is that it does not exist in the pages of a book, within the characters on a stage, or inside the pixels on a screen. It exists solely in the mind, in the individual experiences of the audience. The opportunity to solve the puzzle *with* the characters on screen is arguably the main appeal of any mystery. If *you*, the audience, already know the outcome, then the journey can quickly lose its suspense and become a chore to rehash.

But what if there was some way to to keep the *mystery* in the mystery?

Enter the *Procedural Procedural*. Video games and other interactive media provide us with the unique opportunity to augment the traditional mystery formula. More specifically, they offer the ability for the audience to *become* the detective and interact directly with the investigation. What's more fascinating is that, in theory, it is possible to take the "traditional mystery formula" and use it to procedurally generate a mystery in *real time*.

There is a phrase, "What is easy to say, is hard to do." and I can't think of a better candidate than, "procedurally generate a mystery in real time." As easy as that is to say, it does prove to be a rather difficult premise to tackle.

In this post, we will explore the *cursed* nature of the procedurally generated detective game. We will deconstruct some of the more interesting challenges along the way, and by the end, we will have a deeper insight into the problem as a whole.

## **Exploration**

Before I continue I would like to borrow a couple of definitions from Alex Jaffe's GDC talk on [Cursed Problems in Game Design](https://www.youtube.com/watch?v=8uE6-vIi1rQ).

1. **Player Promises:** *A game's essential experiences. Why the player came to play.*  
2. **Cursed Problem:** *An unsolvable design problem, rooted in a conflict between core player promises.*

 There are *already* hundreds of procedural detective games. Some are good and some are bad, but most share a problem that is, more or less, unique to the detective game genre. In order to break down a "Procedural Procedural", we will have to address not only the broader features of the *mystery genre*, but also specific *detective game* related problems. The first of which being, primarily narrative driven experiences, particularly detective games, tend to suffer from their own "game-ness".

It's nobody's fault that games want to be games, but there is something to say about the inverse relationship between mechanics and narrative. Player agency is all about the ability to make meaningful choices. Unfortunately a strong reliance on narrative structure diminishes the opportunity for meaningful choices to exist.

Therein lies the rub.

At this point, you may be starting to put together why designing *any* detective game is kind of a cursed problem. The core promise of "Become a detective and make meaningful choices in the investigation" is in direct conflict with promise of "Follow a carefully crafted narrative where you are kept guessing until the very end".

Alex Jaffe suggests to us that there are several ways to work with cursed problems; however, any solution will require weakening one or more of our core promises. In a detective game this is typically accomplished by minimizing the player's ability to interact directly with the story. This kind of defensive design usually results in a "back seat" experience, where the player is, more or less, just along for the ride and not directly in control. This is where procedural generation comes into play.

On the surface, a procedurally generated narrative solves so many problems. For the developer, it means dramatically increasing the amount of in-game content at little cost. For the player, it means not getting stuck playing through the same scenario over and over again. And in theory, it allows the game's narrative structure to mend itself *as* player choices continue to break it.

Now, I hear you saying, "Sounds too good to be true. What's the catch?"

The catch here is an inevitable tradeoff. If it wasn't already obvious, in order to strengthen player agency, we have to weaken the narrative structure. I know a procedurally generated narrative doesn't *sound* like it weakens our second promise, but the very nature of procedurally generated content dictates that to increase the *quantity* of output, we must also reduce the *quality* of output (and visa versa). Fortunately for us, this means the *binary* question of weakening the narrative, instead becomes a question of *degree*.

If we are okay with this compromise, we can start asking more specific questions about *how* to procedurally generate a mystery; specifically while maximizing player agency, and maintaining some narrative direction. 

# [**To Be Continued...**]({{site.baseurl}})

## **Links**
Alex Jaffe's GDC talk on [Cursed Problems in Game Design](https://www.youtube.com/watch?v=8uE6-vIi1rQ).  
