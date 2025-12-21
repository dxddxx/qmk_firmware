# QVMP layout by dxddxx

### target audience: standard ansi qwerty laptop keyboard users who touch type with correct fingers and practices good habits

- ansi macbook keyboard with no remap is an example of a standard qwerty laptop keyboard
- correct finger is typing 1qaz and 0p;/ with pinky, 5tgb and 6yhn with index, and the rest follows
- good habits includes using the opposite hand to press shift while typing caps or symbols, e.g. ! and A with right shift
    - well established single hand operations like cmd+shift+4 and cmd+minus and cmd+equal are also considered good habits
- examples of who this is not for:
    - non qwerty users
    - split keyboard users
    - people who are fine with pressing -= with left hand

### target hardware: uni body ansi qwerty keyboard of size ≥ my ideal keyboard

- includes ansi qwerty keyboards from 40% to 100%, planck, peronic, laptop keyboard, thinkpad keyboard ... other common layouts
- my ideal keyboard:
    - 4x10 ortho, with 26+4 alphas, mods, space, and 2 mouse keys (optional)

### features designed according to target audience and hardware:

1. keyboard size: 26+4 alphas, bottom row mods, space for both thumbs
1. no brainer non-layer access to big keys:
    - combos: (we) for enter, (sd) for tab, (io) for backspace, (kl) for enter
    - mod taps: z and / for shift
1. bottom row is kept clean, bottom row mods and space does exactly the same thing as standard keyboard
1. function layer:
    - function keys on q row, therefore hjkl for arrow, therefore semicolon is the only key to enter function layer so that I can arrow with single hand
    - semicolon is also very unused, hard to trigger layer on accident
    - both shift available in function layer
    - made similar to a function layer of a 60% keyboard
1. alternate hand symbols layers: (see layer 1 and 2 in keymap.c)
    - ensures all numbers can be typed with single hand, correct finger
    - ensures -=[]\ cluster on right hand
    - encourages opposite hand shifting for shifted symbols
    - ensures thumb is left unused, so cmd+shift+number and zooming shortcuts are easy
1. why qvmp for symbol layer keys:
    - 4 layer keys, one for each indexes and pinkies is required to ensure single hand numbers with correct finger
    - the only keys left available are qa rfv ujm p
    - since p is the only choice for right hand pinky, q would be for left hand pinky for symmetry, q is also less used than a
    - v and m is the least used in their columns, (j is held for vim, so j is not the least used in its column), so using v and m reduces miss triggers
    - on uni body keyboards, arms point inwards, so qvmp is more ergo than afj;

Honestly all keyboard layouts are good once you get used to it, I try to make mine easy to switch between this layout and standard ansi qwerty layout. This layout isn't without hacks though, I still added a toggled numbers layer for typing in long strings of symbols or numbers, and I find myself shamefully using that layer sometimes. I try to use these theories to explain why my layout is good but honestly they are still made for my own habits, good or bad. However, I do think it's important to be critical of your layout, find imperfections (like not being able to do certain shortcuts with a single hand), set design principles, target audiences, and come up with a layout based on your theory. Yes you will still come up with a crap layout that only you can get used to but at least now the design follows a consistent principle and there is a clear direction for it to evolve.
