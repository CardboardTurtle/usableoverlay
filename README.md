# usableoverlay
the only usable overlay gamepad for retroarch

**Please note**

make "Y" map to "B" in controls for cores just A and B buttons, like NES and the Gameboys
explanation is under the screenshots.
A on the overlay is mapped to A, but B on the overlay is mapped to Y. Make sure that in the keybind settings on your retroarch that the Y button is mapped to "B" for the cores that you would use this overlay for.

**disclaimer**

this is about as much of a replacement for a controller as a ryzen 3 is a replacement for a ryzen 5. it not as capable, but its good enough to do most things, and in a few things you won't even tell the difference. don't expect this to be just like a real controller, but do expect it to be decent enough to actually enjoy playing games.

**how it works**

only enough buttons for GBA emulation. AB, LR, Start/Select, and d-pad.
basically the same thing as a gameboy layout, but the AB buttons are mirrored. Instead of A being to the top right of B, its to the top left. this makes it easier to hold B and press A, like how you need to for platformers.
not only this, but theres a small overlap on the A and B button hitboxes. This makes it even easier to press both buttons at once. its not large enough that you'll accidentally press both buttons, but its large enough to make the overlay usable.

there are no other overlays like this that i have found, which is surprising. because of this, im calling this one the only usable overlay for retroarch, soley because of being able to press A and B at the same time.
playing mario is actually possible now.
**SCREENSHOTS:**
![Screenshot_20210629-000938_RetroArch](https://user-images.githubusercontent.com/43497630/123741383-92c0a400-d86f-11eb-8339-6beecaf2d5f2.png)

![Screenshot_20210629-001435_RetroArch](https://user-images.githubusercontent.com/43497630/123741388-97855800-d86f-11eb-8bac-9aab072bde92.png)


**explanation for why mappings are weird**

tldr: shits fucked.
when using an overlay controller, a remapped key does not behaved as its supposed to. basically, when you press a button, that button is pressed. On the Mario 3 map, pressing "B" on the overlay will by default open up the items menu, and "A" would open a level. You can remap the keys so that instead of B and A you can choose any other inputs. This works completely fine while using a controller. HOWEVER, using an overlay kinda doesn't do that. When using an overlay, pressing B will ALWAYS be B. This is problematic if you use a sane key configuration like using Y and B as B and A, similar to Mario World and all mario games after that.
When pressing B after setting to A, Retroarch actually presses both B and A instead of just A. This not only messes stuff up a little bit, but makes some games not function entirely, such as Mario 3. You cannot even enter a level with this glitch going on since all attempts to press A to enter would just open up the item drawer. To compensate, the overlay uses A as A, which is usually always just "A," and Y as B, which is what non-disabled people would have it set to anyways. With all of this put together, the overlay functions as it should be, assuming you actually remap the keys like someone without a mental disorder.
