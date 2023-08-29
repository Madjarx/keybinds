# Visual Studio code keybinds for my Mac - from a former WoW Arena Healer

Still a WIP, thinking bout it before i hit the hay. Planning on making the best ever set of keybinds.
If i spent 3 days analyzing the anatomy of palms and fingers & keyboard ergonomics for my hpal, i can document at least the binds that i use the most for coding.


## This is only a small POC

I still have a long long way to finalize my keybinds layout. Writing code in different occasions requires different keybinds. This one shall be the "universal" one till i figure out a system that will suit my needs better.
This keybind system is based on the Mac styled, half-profile keyboard (THAT IS NOT MECHANICAL!!!). 

Since we're using all the funny stuff in coding, i can't really tick off the tildas or shabang symbols, but luckily Mac has plenty of keys to spare (I will go for international styled keyboards since i got
big hands and got used to it already, it adds one or two keys that wont ever be used at all, on ergonomically reachable spaces);

I will try to go with the following:
- Base Invokators - Buttons that will serve as the base for keybinds. CMD, Alt, Shift and Control all have different "weight"
- Follow up bind - Buttons that resemble the action in some manner, but are ergonomically suited for that situation.
- Modifier - Button that modifies the action, most suited example would be fold/unfold - where a button would serve as a reverse modifier


Example being:
```
If im navigating through the files, i prolly have both my hands at the center of the keyboard, meaning i can hit the key groups at the edge of the keyboard as they are the fastest to hit.
```

Avoid using `SHIFT` and dont get used to it a lot, it can be used in non-often, 3-key keybinds. We need it quite a lot
`Shift` is usually my modified in actions that are resembling recursive / are prone to cycling, such as folding/unfolding regions. 

### Here's my shot:

### Best friend:
- `cmd + shift + p` - your best friend

### Left / Right Between tabs:
- `cmd + shift + [` - navigate to tab on left
- `cmd + shift + ]` - navigate to tab on right

### Moving the Tabs around - < > buttons :
- `cmd + ,` - move the editor tab to the left
- `cmd + .` - move the editor tab to the right

### Focus editor group on right / left:
(I prolly wont resort to these a lot, mostly my group oriented binds contain `CMD` and `[`&`]` symbols in one form or another)
- `option + tab` - focus next editor group (i can use this one to just cycle through all the groups, i have only two open at all times mostly)
- `shift + option + tab` - focus previous editor group (in case i fuck up)

### Focusing the groups:
- `option + CMD + [` - focuses the group on the left
- `option + CMD + ]` - focuses the group on the right

### Splitting into groups: 
I should use `MoveEditor` instead of `SplitEditor` since move one actually moves the tab, i dont need additional 6 keystrokes to close the previous one
- `CTRL + CMD + ]` - move editor into RIGHT group (move it or open in a new group if theres none on that side) 
- `CTRL + CMD + [` - move editor into RIGHT group (move it or open in a new group if theres none on that side) 

to be continued...


