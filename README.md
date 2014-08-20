# The Ultimate Game Development Course

Game development is awesome. There are lots of things to read and know, best practices, great tools, and other useful "stuff." This page attempts to give you a bare-bones "course" which takes you from initial idea through to implementation.

Sections are ordered *chronologically*, in the order that you would *need* them.

Ready? Here we go.

# Essential Tools

These tools cross boundaries across platforms. Learn them well; you will use them extensively.

- [Audacity](http://audacity.sourceforge.net/): possibly the best free audio editor around. Also works as a convenient converter between MP3/WAV/OGG files.
- [GIMP](http://www.gimp.org/): Excellent, free image editor, oft-quoted as a free substitute for Photoshop.
- [Tiled Map Editor](http://www.mapeditor.org/): an excellent and versatile 2D map editor for tiled maps. Usable enough for concept or prototype art; functional enough to create production game maps.


# Essential "Theory"

Game design is a field which is increasingly attracting smart analysis; there are some good ideas about how to design better games.

Read as much of the below links as you can; they all talk about fundamental underpinnings in games (eg. what is "good" vs. "bad" difficulty in games).

- [Understanding Randomness in terms of Mastery](http://www.lostgarden.com/2012/12/understanding-randomness-in-terms-of.html): An explanation of noise, mastery, mental models, and how they go together; how to use random so that unskilled players learn and become skilled players (build mental model, master randomness).
- [Steambirds: Survival Mode](http://www.lostgarden.com/2011/10/steambirds-survival-mobile.html): An explanation of “arrow of play” -- defining gameplay as a step by step progression, so players know where they are and where they’re going.
- [Making them Work for it: Designing Achievements for your Games](http://gamedev.tutsplus.com/articles/game-design-articles/make-them-work-for-it-designing-achievements-for-your-games/): What achievements are, and how to design achievements -- good (promote unique gameplay; mark progress), bad (force linear gameplay or bad behaviour), and ugly (chicken kicking?!).
- [Hard Mode: Good Difficulty vs. Bad Difficulty](http://gamedev.tutsplus.com/articles/game-design-articles/hard-mode-good-difficulty-versus-bad-difficulty/): An explanation of difficulty (requires more user skill), good (developed/designed) vs. bad (artificial: just increment sliders), and why it matters (normal game is balanced, unfair feeling of difficult = lame).
- [Easy Mode: When is Easy Okay?](http://gamedev.tutsplus.com/articles/game-design-articles/easy-mode-when-easy-is-okay/): the second part of the above series. Talks about crafting difficulty around the experience you want to build, not tweaking it just to try and make it more accessible to casual players.
- [Evaulating Game Mechanics for Depth](http://www.gamasutra.com/view/feature/134273/evaluating_game_mechanics_for_depth.php): the difference between “shallow” and “deep” mechanics, and how you can use crisp activity statements to build deep mechanics in your games.
- [Slippery Slope and Perpetual Comeback](http://www.sirlin.net/articles/slippery-slope-and-perpetual-comeback.html): Good discussion about “slippery slope” (when losing, it’s harder to make a comeback) and “perpetual comeback” (when losing, it’s easy to have a reversal and win).
- [#1GAM: How to Succeed at Making One Game a Month](http://gamedev.tutsplus.com/articles/business-articles/1gam-how-to-succeed-at-making-one-game-a-month/): great advice on how to stop having 90% of your games fail, and instead, finish and succeed. Written by someone who made 12 games in 12 months in 2012 (yes, yes, I know).
- **Gameplay as skill**: See above article. Consider Mario 64: first level first star requires running, jumping, evasion. Last level last star requires triple-jumping on a dime, then wall-kicking, while you have a blue hat active (limited time).
- [Trust](http://www.youhaventlived.com/qblog/2013/QBlog180213A.html): Some complaints about levelling in MMOs; how you can ditch this and come up with a sensible system that’s skill-based and trust-based. 
- [Designing an Inventory System for your RPG](http://gamedevelopment.tutsplus.com/articles/designing-an-rpg-inventory-system-that-fits-preliminary-steps--gamedev-14725): A summary of common inventory types, and the pros and cons of each; advice on how to evaluate which (or what combination / custom version) to implement in your own RPG.
- [Designing Mini-Games: How to do them Right](http://gamedevelopment.tutsplus.com/articles/designing-rpg-mini-games-and-getting-them-right--gamedev-14226): A discussion on what classes of mini-games exist, and how to pick the appropriate type for your game.
- [A Single Game as a Lifelong Hobby](http://www.lostgarden.com/2013/07/a-single-game-as-lifelong-hobby.html): How evergreen (skill-based) games attract lifetime, often competitive, gamers.
- [Goal Oriented Action Planning for Smarter AIs](http://gamedevelopment.tutsplus.com/tutorials/goal-oriented-action-planning-for-a-smarter-ai--cms-20793): How to create "goal-oriented" AI agents that are more realistic, and use their goals to determine their actions.
- [The Guide to Implementing 2D Platformers](http://higherorderfun.com/blog/2012/05/20/the-guide-to-implementing-2d-platformers/): An anaysis of how to implement a platformers; analysis of some existing styles, with analysis of design trade-offs.
- [On the Shoulders of Giants](http://blog.rpgmakerweb.com/tutorials/on-the-shoulders-of-giants/): game developers copy ideas from other soften. This article explains how to examine the benefits, improve, change, and recast copied ideas into something better.
- [The SnowBall Effect](http://gamedevelopment.tutsplus.com/articles/the-snowball-effect-and-how-to-avoid-it-in-game-design--cms-21892): how to use (and avoid) creating a snowball effect in your games for more epic comebacks.

# Core Mechanic

Great games start with a great core mechanic, the "thing" you do over and over again. In Tetris, you rotate and place blocks as they fall. In Mario, you run and jump to the end.

Get your core mechanic right, because it makes or breaks your game. When you take away the graphics, audio, achievements, etc. what you have left is your real core game. That's your mechanic, that  players play over and over again.

Once you have a decent idea of how your game works, move to the next section.

# Concept Art

You have an idea; now make it more real and vivid through concept art. This will help you flesh out parts of your idea; more importantly, it will **keep you motivated** through the long, thankless job of *shipping that idea.*

Create concept art that illustrates the major points of your game and motivates you to get it done.

Note: **Please respect copyright.** Don't use other peoples intellectual property, especially in commercial games, without their prior permission. For quick concept art, it may suffice. Some sites, like Getty Images, prohibit use even for concept imagery beyond 60 days. Consult with a lawyer.

**Note:** Also take a look at the resources under Main Development.

- [Google Image Search](http://images.google.com/): Awesome way to find good images, but not very specific ones.
- [Getty Images](http://www.gettyimages.ca): Awesome way to find very specific images; important search words are "nobody" and "single object only".


# Early Development / Prototyping

Your idea is ready; you have major points of the main gameplay fleshed out, complete with some inspirational art. Create the smallest possible prototype version of your code that you can imagine.

Is your core mechanic great? Chances are it needs work. This is the time to tweak it and change it. If it's fun with placeholder graphics and no sound, it'll be amazing with the full, final production.

The goal here is to **trade quality for speed.** The quicker you make your game, the faster you can tell if it's awesome, or less so. Don't worry about code quality, unit testing, or any of that other stuff; just make sure you have something playable and it's *fun.*

Some technologies which are useful for fast/cheap prototyping:

- [CraftyJS](http://craftyjs.com/): Javascript game library with entity/component architecture and event-based messaging. You can create reusable components and parameterized entities, and game development is quite fast. You can also evolve/rewrite your code into production code (complete with unit testing) if you decide to stick with this platform.
- [LÖVE](http://love2d.org/): Lua game development library. Many swear by it.

# Main Development

You modified and verified your idea by making it into reality, and saw that it works, and works well. Now grind that thing out to completion. Games are not just core gameplay, but they include art, sounds, screens, and many things that you need to do.

You may want to completely rewrite your game in a different technology to make it production-ready (eg. something more cross-platform/solid/fast/low-level/etc.), or you may want to heavily modify your existing code to bring it up to standards. 

## Essential Reading

- [I have to make a game in 9 days. AHHH!](http://gamedev.stackexchange.com/a/24916/1929): some good advice on completing a game in nine days or less. The same principles apply to completing games *at all*; games tend to balloon in size and fail. Keep it small and trim ruthlessly.
- [Should you Polish your Game, or add more Depth and Features?](http://gamedevelopment.tutsplus.com/articles/should-you-polish-your-game-or-add-more-depth-and-features--cms-21155): A good set of guidelines to help you decide if you should polish your existing game or add more depth/gameplay/features.


## Awesome Tools and Resources

- [BFXR](http://www.bfxr.net/): quickly create decent sound-effects for your game.
- [CG Textures](http://www.cgtextures.com/): Free, quality textures for 3D (and other) work.
- [Cool Text](http://cooltext.com/): Create nice customized text-logos (including animated ones).
- [FreeSound.org](http://freesound.org): download sounds toand compose awesome background ambiance.
- [Font Squirrel](http://www.fontsquirrel.com/): beautiful collection of fonts, 100% free for commercial use.
- [Google Fonts](https://www.google.com/fonts): Excellent collection of fonts with very permissive licensing/terms of usage. Yes, you can download the fonts too.
- [IconFinder](https://www.iconfinder.com/): Great way to find small, free (and paid) icons that you can use in your games.
- [The League of Movable Type](https://www.theleagueofmoveabletype.com/): An awesome, but small, list of free-for-use fonts.

# Finishing Touches
Your game is pretty much done. There's still a lot of stuff you can do to make it better -- smaller, faster, etc.

- [TinyPNG](https://tinypng.com/): Compresses all your PNGs in a loss-less way. Saves tons of bytes.
- [Coblis Color Blindness Simulator](http://www.color-blindness.com/coblis-color-blindness-simulator/): upload screenshots of your game and make sure it looks okay to someone with colour blindness. (Red-blind and green-blind are the most common.) Also, [ask on reddit](http://www.reddit.com/r/colorblind) for someone who's colorblind to take a look at your game.

# Pre-Release

Finally, your game is complete! You need to prepare it for your marketing push.

- **Write up a project retrospective:** get (candid, if possible) feedback from everyone (all team members regardless of position/role) about the project. What went well? What didn't go so well? What would we do differently next time?
- [6 Simple Things You can do to Improve Your Screenshots](http://gamedevelopment.tutsplus.com/tutorials/6-simple-things-you-can-do-to-improve-your-screenshots--gamedev-14272): useful for marketing materials.

# Specific Platforms and Styles

For a list of advice for specific types of games (eg. kids games, Android games, RPG Maker games) see [the wiki](https://github.com/ashes999/game-development-course/wiki).
