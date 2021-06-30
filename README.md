# usableoverlay
the only usable overlay gamepad for retroarch

MAP X TO B IN CONTROL SETTINGS FOUND IN THE QUICK MENU (PRESS RETROARCH LOGO DURING PLAY) IF YOU WANT NES GAMES PLAYABLE IN PORTRAIT MODE.

**disclaimer**

this is about as much of a replacement for a controller as a ryzen 3 is a replacement for a ryzen 7. it not as capable, but its good enough to do most things, and in a few things you won't even tell the difference. don't expect this to be just like a real controller, but do expect it to be decent enough to actually enjoy playing games.

**how it works and why its the best one**

There a small overlap between the buttons. This makes it actually possible to press both buttons at once. This way, you can run and jump at the same time, something necessary to play many games.

The button placement is also a large part of it. I used Super Mario Bros. 3 as the test game while designing the overlay, so i placed the buttons in a way most useful for that game. whats best for mario 3 is best for pretty much all other mario games.

**SCREENSHOTS:** taken with my oneplus 7 pro

![Screenshot_20210630-142924_RetroArch](https://user-images.githubusercontent.com/43497630/124020364-d02c4b00-d9af-11eb-89bc-ba94b4ccaaad.png)

![Screenshot_20210630-141032_RetroArch](https://user-images.githubusercontent.com/43497630/124018952-0cf74280-d9ae-11eb-99c9-cf11285feb7a.png)

there are no other overlays like this that i have found, which is surprising. because of this, im calling this one the only usable overlay for retroarch, soley because of being able to press A and B at the same time.
playing mario is actually possible now.

**why reverse the buttons?**

The buttons are reversed like this because of the mario games. pressing the rightmost button and hovering the leftmost works much better than pressing leftmost and hovering the rightmost button, mostly because of the "input lag" problems with touch overlays. Whenever using a touchscreen overlay, theres going to be more "input lag" than when using real buttons. not because of the technology behind the overlays, but because of the technology behind your thumbs. moving your thumb down and in on itself takes more time than down and flattening it out on the screen. Because of this fact, I reversed the layout.

**a brief note about Super Mario Kart and other games that use the shoulder buttons**

you might think that its impossible to play these games because of how far up the shoulder buttons are, but if you use this for five minutes you'll figure out that you can just hover over the L and R buttons. this is even easier if your phone has curved bezels, or a slim case on it.

Alternatively, you could use external shoulder buttons. I have found three solutions and have tried none. Use at your own risk.

https://www.amazon.com/Controller-Transparent-Sensitive-Survival-Joystick/dp/B07CP4BLK9 This is an attachment you buy that could work. about 7 dollars

https://www.youtube.com/watch?v=y02cay9FQes This is a guide on how to make attachments with aluminum tape and masking tape, ive heard gum wrappers also work, and tinfoil or aluminum foil should be fine as well.

https://www.thingiverse.com/thing:3238515 This is both. you 3D print a mechanism, then wrap the conductive material like the ones discussed above around it. you would have to edit the file to match your phone's depth, though. If you don't have a 3D printer, check your library. some libraries have 3D printers now.

**why are the buttons staggered in portrait, but not in landscape?**

early in development, even before I knew how layers worked, I had decided that portrait was to be used for Gameboy and NES games, while landscape _could_ be used for SNES and DS if I were to figure them out. Well, I did figure them out, and in V2 it was like the original vision. However, two days later, I realized that was stupid and I could very easily support SNES games (at least a little bit) in portrait because of how much space was available on the screen, without any (or with very little) negative effect. So I put in SNES support for portrait after getting landscape to work. However, I learned that in portrait mode by moving the buttons up it became much harder to keep my thumb in the right location, and I kept triggering the overlaps from the B and Y buttons. As such, I staggered them out a bit so that this problem went away.

I had staggered the SNES buttons in landscape before out of fear of the problems i encountered in portrait, but turns out, its much easier to avoid misplacing your thumb in landscape. Plus, by unstaggering I made Super Mario Kart much more playable.

You won't be able to play super mario kart in portrait, but you should be able to play a significant amount of games including Mario World, Zelda, RPGs, visual novels, and many more that don't require B and A or Y and X to be pressed at the same time. Of course, its less comfortable to play mario world in portrait because you use Y and B instead of X and A because spin jump, so it all depends on the game as to what layout works best.

**why use mario as a basis for development?**

let me preface this with i didn't just use mario, i messed about a bit in some other games, like Super Mario Kart. That being said, I did primarily use Mario as the main test game.

because its one of the most popular series of games to play, and most action games require very, very similiar motions to mario. Contra, for example, is also A to jump, and B to shoot. the only difference is the lack of running. Top-down games like Zelda have less of a need for specific button layouts, since each press is usually independent of the other. RPGs don't even need a cohesive button layout because theres no real rush to press the right button at the right time.

You're not gonna care where the A and B buttons are while playing Ace Attourney, but youre gonna care when you need to jump across a huge gap at just the right moment in Super Mario Bros.

**extra info you might like**

the squares on the dpad are up+left and down+right and such, and there is in fact a refresh button. its just invis. next to the menu and fast foward buttons. invis because it would likely never be used, but still to have just in case.
