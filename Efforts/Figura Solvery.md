# Solvery

- [x] Armor Hider Action wheel
	- [x] for armor pings, consolidate into one ping, and use if, function data send
- [x] Horn
- [ ] Ears
- [ ] Tail
- [ ] Tail physics
- [ ] Faces
- [ ] Emotes
- [ ] Chest
- [ ] Animation pack
- [ ] Skin swapper wheel

Rusalka
- [x] Ears
- [ ] Ear wiggle,
	- Done through animation
- [ ] Tail?
- [ ] Shark Tail?
trans
- [ ] hair
- [ ] eyes
narwhal chans 
- [ ] armor toggle
- [ ] skin toggle
- [x] horn
frozen tundra
- [x] horn
- [ ] animations
Kal'tsit
- [ ] Hairs
- [ ] Tail
- [ ] Shirt physics
- [ ] scarf
- [ ] ears
- [ ] expression
Starhorn
- [ ] physics


--[[
    Because flat parts in the model are 2 faces directly on top
    of eachother, and have 0 inflate, the two faces will z-fight.
    This prevents z-fighting, as well as z-fighting at a distance,
    as well as translucent stacking.
    Please add plane/flat parts with 2 faces to the table below.
    0.01 works, but this works much better :)
--]]

local planeParts = {}