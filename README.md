# "The Code Awards 2023": EVASCode

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=tecnomazov.evas-code">
    <img src="https://github.com/JuditKaramazov/TCA-EVASCode/blob/9b562843a9a863ff4d93843453f370f34e8a0ed5/images/EVASCode.png" width="300" height="300" alt="EVASCode original logo.">
  </a>
</p>
<h1 align="center">
  EVASCode <br />
  "The End of Development"
</h1>
<div align="center">
  <img src="https://img.shields.io/badge/VSCode-VSCode-1575F9?logo=vscode" alt="VSCode" title="VSCode" />
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT" title="License: MIT" />
</div>
<br />
<p align="center">
  <a href="https:/github.com/JuditKaramazov">🐱 /JuditKaramazov</a>
</p>
<p align="center">
  <a href="https://karamazfolio.xyz/">📍 Personal site</a>
</p>
<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=tecnomazov.evas-code">⬇️ Package</a>
</p>

---

This repository serves as a versatile package of themes designed specifically for [Visual Studio Code](https://code.visualstudio.com/), offering a range of aesthetic choices to suit your coding environment. The themes are primarily built using JSON files, ensuring simplicity and compatibility across various setups. Happy coding! 🚀✨

Oops, and just in case...:

<div align="center">
    <b>⚠️ SPOILERS AHEAD! ⚠️</b>
</div>

## Getting Started

Aren't we here to make other people's lives easier? No doubt! That's why, if you only want to download and test the themes in your favourite editor, you have the option to install and enjoy them directly by following some simple steps:

1. Download the themes in the [Marketplace](https://marketplace.visualstudio.com/items?itemName=tecnomazov.evas-code).
2. Now... now... well, that's it! Or `almost` it; press <kbd>⌘,</kbd>, look for `Workbench: Color Theme`, and choose one of the following:

- EVA-00
- EVA-01
- EVA-02
- The End of Development

If you feel curious about the process of crafting your themes instead, start by cloning this repository to your local machine using Git. 

Open your terminal and run the following command:

```bash
$ git clone https://github.com/JuditKaramazov/TCA-EVASCode.git
```

Then, in your terminal:

```fish
cd EVASCode
npx vsce package
```

This will allow us to package our themes into a .vsix file. Finally:

```fish
code --install-extension evas-code-0.0.1.vsix
```

Now, you are ready to run and test the themes locally. Bear in mind that VSCode does not provide a direct way to preview theme changes in real-time without packaging and installing the extension, but if you want to keep track of your changes and additions without constantly packaging, installing, and restarting your editor, you can simply create a new instance of VSCode, press `F5` (or `Run` menu), open a new `Development Host` window and, finally, `Start Debugging`. After making changes to your theme files, you can reload the extension by clicking the refresh icon in the top left corner of the instance launched in development mode, which facilitates _a lot_ the testing process. Remember, however, that this method is for previewing changes during development; once you are satisfied with the changes, you would still need to package and install the extension for others to use - like me! _All of us, all of us, all of us..._

## Introduction

<p align="center">
  <img src="https://github.com/JuditKaramazov/TCA-EVASCode/blob/9b562843a9a863ff4d93843453f370f34e8a0ed5/images/EVASCode-01.png" alt="EVASCode visual asset." > 
</p>

"Why do you pilot an EVA?"

"Oh, wait. Wait... What happened?! Is Codetopia finished already, Judit?” Not in our hearts, that’s for sure, but now that December has become an unavoidable reality, it seemed appropriate to collect some Christmas decorations (from last year*, and from the one before, and...), a nice (and imaginary) suit, and then start fantasizing with the idea of delivering `The Code Awards` to the unlucky ones having to deal with my nonsensical experiments day after day. As you surely know, and as it became a must in the video game sector, [The Game Awards](https://thegameawards.com/) are taking place in some hours, with a more or less satisfactory amount of decent nominees considering the nature of the event itself. However, although I’ve been using these events as an excuse that allowed me to keep on learning and exploring new development areas, technologies, and various tools, this time we are not discussing video games nor questionable events aiming to become the new Oscars (note to my future self: I still hate you, Geoff, but you can conquer my heart again by releasing a _noice_ trailer of Elden Ring's DLC).

Quite a long while ago, right when the illusion of self was shattered, I ceased to be - and yet I embraced two great animes without taking into account my own timing nor the implications of my acts during such a delicate state: `Evangelion` came first, and then `Berserk` arrived to insist on the fact that, independently of how things might seem at the moment and just like Senua would say, "the hardest battles are fought in the mind, not with the sword". Similarly, after several missed occasions when I managed to convince myself about Evangelion showcasing gigantic robots _and that's all about it,_ my best friend reminded me of the existence of his favorite anime. For once, I followed his advice without finding myself any excuse. Which one would I create when I had no mental energy left, anyway? Robots not being to my liking? Despair, the lack of purpose, the absence of any answer when asked "Why do you pilot an EVA?"

Surprisingly (or not so), he was terribly right: there were indeed mechas, but the entirety of Evangelion had nothing to do with robots slapping their faces without any context, purpose, or reasoning behind their actions and existence. Furthermore, one of the reasons why Evangelion is so profound is that it functions on no fewer than four distinct allegorical levels: it can be enjoyed at face value as an expertly realized sci-fi action adventure, but it is also a dystopian satire of the genre. And a coming-of-age parable. And a treatise on confronting loneliness and uncertainty in the adult world. And - alright, _alright._ We all know how vast Evangelion's symbolism is, and it would be quite pretentious if I treated my README.md file as some sort of academic paper discussing the presence (or absence) of Lacan, Freud, Hegel, and so many other thinkers in Evangelion's main themes and imagery. Imagine that a bond could be created after such a proof of intimacy. Imagine the dimensions of the following discontents. 

Let's remain here, keeping a safe distance. Is it the world we wished for? "You can't bridge the gap between your own truth and the reality of others", isn't it? "A place with no AT Fields, where individual forms do not exist. An ambiguous world where you cannot tell where you end and others begin. A world where you exist everywhere, and yet youʼre nowhere, all at once."
Now, why do you pilot an EVA?

## Features

"This is the world you wished for."

<p align="center">
  <img src="https://github.com/JuditKaramazov/TCA-EVASCode/blob/9b562843a9a863ff4d93843453f370f34e8a0ed5/images/EVASCode-03.png" alt="EVA-00 theme visual asset.">
</p>

> But as Shinji soon realizes: 'But this isn't right. This feels wrong.' There is no Otherness in Human Instrumentality. Therein, everyone absolutely understand each other. Even our personal secrets no longer become a secret (...). In the End of Evangelion, Shinji realizes that there never was a need to 'overcome' the gap between the self and the Other. As Rei tells Shinji: 'You can't bridge the gap between your own truth and the reality of others'. True overcoming is rather the realization that the gap was never an obstacle to begin with. For the gap is immanent to the thing itself. If you remove the gap or imperfection from the thing, the thing will disappear as well. If you remove the gap between the self and the Other, you will not unite the two in a harmonious whole. Instead, you will lose both at once.
[Kiwic, 'Intimacy and its discontents: An Essay on Evangelion’s Human
Instrumentality Project'](https://drive.google.com/file/d/1YS0XY1ktnSnRSN9pj4Tsy9psYzMYrJwO/view)

<p align="center">
  <img src="https://github.com/JuditKaramazov/TCA-EVASCode/blob/9b562843a9a863ff4d93843453f370f34e8a0ed5/images/EVASCode-04.png" alt="EVA-01 theme visual asset.">
</p>

> In the final scene of The End of Evangelion, we find ourselves in a lengthy silence. The silence is then broken as Shinji continues to choke Asuka. Instead of defending herself, however, Asuka caresses Shinji's cheeks. This is the first step towards love. This moment is precisely the embracing of the absolute Other (...). Shinji and Asuka, being the only two humans left on earth, will have to learn how to live with each other. Like a married couple who have to find a mode of living with each other: who will do the dishes, who will cook breakfast, etc. We can therefore say that both Human Instrumentality and depression is the inability to love. Likewise, the inability to love leads one to opt one of the two as a solution to the hedgehog's dilemma.

<p align="center">
  <img src="https://github.com/JuditKaramazov/TCA-EVASCode/blob/9b562843a9a863ff4d93843453f370f34e8a0ed5/images/EVASCode-05.png" alt="EVA-02 theme visual asset.">
</p>

## Style

As for the aesthetic decisions, one could say that they were ambiguous, to say the least; while EVA-01 and EVA-02 work like a reliable representation of what each EVA essentially _is,_ EVA-00 and the `Bonus Track`, The End of Development, serve as a personal interpretation of certain scenes, themes, the overall atmosphere and tone, and the characters' role in the story itself.

In order to offer a better understanding of the above-mentioned decisions, here are the main palettes, as well as some notes regarding what _I_ see whenever I pilot these specific EVAs:

1. EVA-00
- ![#D8DEE9](https://placehold.co/15x15/D8DEE9/D8DEE9.png) `#D8DEE9`
- ![#CBD6D7](https://placehold.co/15x15/CBD6D7/CBD6D7.png) `#CBD6D7`
- ![#A5BDD6](https://placehold.co/15x15/A5BDD6/A5BDD6.png) `#A5BDD6`
- ![#759AB4](https://placehold.co/15x15/759AB4/759AB4.png) `#759AB4`
- ![#5E81AC](https://placehold.co/15x15/5E81AC/5E81AC.png) `#5E81AC`
- ![#9590BD](https://placehold.co/15x15/9590BD/9590BD.png) `#9590BD`
- ![#F5BDDA](https://placehold.co/15x15/F5BDDA/F5BDDA.png) `#F5BDDA`
- ![#F5AD43](https://placehold.co/15x15/F5AD43/F5AD43.png) `#F5AD43`
- ![#B63958](https://placehold.co/15x15/B63958/B63958.png) `#B63958`
- ![#2D6187](https://placehold.co/15x15/2D6187/2D6187.png) `#2D6187`

Although it could have been way easier to go for a light theme consisting of white, black, and blueish tones capturing both the mecha and Rei's distant aura, the truth is that I faced some inner challenges while representing the EVA-00. In this case, a good part of the original palette stayed safe and sound, and yet some of Rei's scenes interfered with the creative process and its derivations - to the point that the theme itself resulted in a condensation of how I perceive Rei Ayanami from a chromatic standpoint: the lights, shadows, attitude, answers, the blood. This terrible, bloody eye.
Given that her character arc is one of mystery, introspection, and philosophical exploration, I decided that following an abstract interpretation of the original color scheme, the orange version of it, and some of Rei's chromatic tendencies would be as valid as keeping the original palettes intact. What are we supposed to be? Clones? Clones cloning color schemes? (_Oh, God. I can't stand my own sense of humor._)

2. EVA-01
- ![#C99EC7](https://placehold.co/15x15/C99EC7/C99EC7.png) `#C99EC7`
- ![#B0A8DB](https://placehold.co/15x15/B0A8DB/B0A8DB.png) `#B0A8DB`
- ![#986FD8](https://placehold.co/15x15/986FD8/986FD8.png) `#986FD8`
- ![#7F47CF](https://placehold.co/15x15/7F47CF/7F47CF.png) `#7F47CF`
- ![#E091FF](https://placehold.co/15x15/E091FF/E091FF.png) `#E091FF`
- ![#FA04D3](https://placehold.co/15x15/FA04D3/FA04D3.png) `#FA04D3`
- ![#F5AD43](https://placehold.co/15x15/F5AD43/F5AD43.png) `#F5AD43`
- ![#55FF00](https://placehold.co/15x15/55FF00/55FF00.png) `#55FF00`
- ![#58BD3C](https://placehold.co/15x15/58BD3C/58BD3C.png) `#58BD3C`
- ![#4BA428](https://placehold.co/15x15/4BA428/4BA428.png) `#4BA428`

I'd want to say that I'm sorry for using such strident tonalities, but actually, `I am not!` All jokes aside, and as stated before, I intended to keep this specific EVA (_my_ EVA, huh?), as well as Asuka's, as close to the original models as possible. I understand that it can be a little bit too much for some delicate retinas, and yet there's no way I'd miss the opportunity of graphically communicating the savageness and implicit (explicit, too) monstrosity in the design and color scheme of the EVA-01. Why? Because even though the pseudo-religious storyline and iconography can fuel most of our nightmares quite a lot already, the series' uniqueness exists also in the mecha design, as well as the nearly animalistic battle frenzy some of these "bio-mechanical creations" get to experience. EVA-01 is one of our first interactions with this openly disturbing nature so closely related to what we could consider body horror - and the way it captures such atmosphere and reality goes beyond actions themselves. Terrible and visceral beyond doubt, this one. Captivating.

3. EVA-02
- ![#ECE3DC](https://placehold.co/15x15/ECE3DC/ECE3DC.png) `#ECE3DC`
- ![#80BDA9](https://placehold.co/15x15/80BDA9/80BDA9.png) `#80BDA9`
- ![#E36526](https://placehold.co/15x15/E36526/E36526.png) `#E36526`
- ![#E92224](https://placehold.co/15x15/E92224/E92224.png) `#E92224`
- ![#B62140](https://placehold.co/15x15/B62140/B62140.png) `#B62140`
- ![#46405A](https://placehold.co/15x15/46405A/46405A.png) `#46405A`

Assertiveness. Confidence. Sometimes a confrontational attitude, too. The colors might indeed symbolize Asuka's boldness and intensity, and if we don't resist this approach, why would we stop ourselves from preserving it, right? There are times when I see similar colors from my balcony, too: the ones that belong to a well-established brand I won't mention here without a previous sponsorship. Such a palette is undeniable to the sight, and since it can be seen, there's no doubt it represents a specific attitude, too. What we see is what it is - but is it? A confident and boastful exterior can serve as a defense mechanism to mask our internal struggles and vulnerabilities, most of the time. A great shield - and the chosen palette contributes to keeping it as solid as undeniable to our eyes.
Do you remember Majora's Mask, though? 
> Your true face... What kind of face is it? I wonder... The face under the mask - is that your true face? 

4. BONUS TRACK: The End of Development
<p align="center">
  <img src="https://github.com/JuditKaramazov/TCA-EVASCode/blob/9b562843a9a863ff4d93843453f370f34e8a0ed5/images/EVASCode-02.png" alt="The End of Development theme visual asset." > 
</p>

- ![#FAF4ED](https://placehold.co/15x15/FAF4ED/FAF4ED.png) `#FAF4ED`
- ![#F2E9E1](https://placehold.co/15x15/F2E9E1/F2E9E1.png) `#F2E9E1`
- ![#C9221E](https://placehold.co/15x15/C9221E/C9221E.png) `#C9221E`
- ![#932224](https://placehold.co/15x15/932224/932224.png) `#932224`
- ![#372021](https://placehold.co/15x15/372021/372021.png) `#372021`
- ![#802B5B](https://placehold.co/15x15/802B5B/802B5B.png) `#802B5B`
- ![#A877B1](https://placehold.co/15x15/A877B1/A877B1.png) `#A877B1`
- ![#797593](https://placehold.co/15x15/797593/797593.png) `#797593`

Previously, I explained that I struggled with the design of the EVA-00 as it didn't allow me to dive deep enough into my personal creative process. It was thanks to this inner confrontation that I realized that while trying to represent the mecha itself, Rei's constant interferences twisted the final result until it became a mashup of my approach to her arc, and that's why I focused on the images catching my attention the most in order to figure out what my interpretation looked like. A poster displaying Asuka and Shinji, a shore? Not quite. In this case, the chore reference is a specific moment involving a reddish eye from the _End of Evangelion_, mostly based on white tones and traces of purple due to Rei Ayanami's presence. As unsettling as calming as it is, that scene still brings back to mind the same old question: the world "we" wished for. Is it?

Dear stranger: why do you pilot an EVA, if I may ask?

## And the award goes to...

Now, the Promised Time: I already expressed the importance of keeping EVA-01 and EVA-02 as intact as possible, and if I made this decision (which I hope to be the right one), it's only because they refer to what I called "my" and "your" mecha. Given these hints, `The Code Award` _undoubtly_ goes to `Kernelkun`, the person who made me realize both my passion towards Evangelion and the fact that I am (not) alone. I (do not) have to be a hero.

Thank you.

As for the rest of you guys, please note that while I'm trying my best to improve and explore different possibilities, there might be some inconsistencies, bugs and errors that will surely be addressed in the future. Do not hesitate to let me know about it, though! If necessary, you can open an issue, and I'll gladly try my best to make these themes as consistent as possible.

Oh, and remember that you can make the Dinosaur extremely happy if you...
<br />

---

<h1 align="center">
  <a href="https://karamazfolio.xyz/"><img src="https://github.com/JuditKaramazov/JuditKaramazfolio/blob/a7b1825e33711948f51e53e249751761e1779f56/public/karamaBrand.png" width="100" height="100" alt="Original logo asset.">
</h1>
<h2 align="center">
  <a href="https://www.buymeacoffee.com/JuditKaramazov" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 207px !important;" ></a>
</h2>
