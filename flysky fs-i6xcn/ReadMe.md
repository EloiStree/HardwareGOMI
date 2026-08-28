```
flysky fs-i6xcn
```

[<img width="900" height="900" alt="image" src="https://github.com/user-attachments/assets/e323333d-e7dc-4edb-a85c-dc0a6f270f91" />](https://www.flysky-cn.com/fsi6x)   
https://www.flysky-cn.com/fsi6x      


```
FILE>>>|.ab_input_to_command
## Full Left Switch two state
flysky fs-i6xcn|s0|b1♦️ false ♦️ cmd:log swa up
flysky fs-i6xcn|s0|b1♦️ true ♦️ cmd:log swa down

##  Left Switch two state
flysky fs-i6xcn|s0|b3♦️ false ♦️ cmd:log swb up
flysky fs-i6xcn|s0|b3♦️ true ♦️ cmd:log swb down

##  Right Switch three state
flysky fs-i6xcn|s0|b4♦️ true ♦️ cmd:log swc up
flysky fs-i6xcn|s0|b4♦️ false ♦️ cmd:log swc up to center
flysky fs-i6xcn|s0|b5♦️ false ♦️ cmd:log swc down to center
flysky fs-i6xcn|s0|b5♦️ true ♦️ cmd:log swc down

## Full right Switch two state
flysky fs-i6xcn|s0|b7♦️ false ♦️ cmd:log swd up
flysky fs-i6xcn|s0|b7♦️ true ♦️ cmd:log swd down


## Top Left Rotation Resistor
flysky fs-i6xcn|s0|a4 ♦️ in ♦️ -0.7 ♦️-0.5 ♦️  cmd:log VAA nw
flysky fs-i6xcn|s0|a4 ♦️ in ♦️ -0.5 ♦️-0 ♦️  cmd:log VAA ne
flysky fs-i6xcn|s0|a4 ♦️ in ♦️ 0 ♦️0.5 ♦️  cmd:log VAA se
flysky fs-i6xcn|s0|a4 ♦️ in ♦️ 0.5 ♦️-0.7 ♦️  cmd:log VAA sw

## Top Left Rotation Resistor
flysky fs-i6xcn|s0|a4 ♦️ in ♦️ -0.6 ♦️-0.4 ♦️  cmd:log VAA n
flysky fs-i6xcn|s0|a4 ♦️ in ♦️ -0.1 ♦️0.1 ♦️  cmd:log VAA e
flysky fs-i6xcn|s0|a4 ♦️ in ♦️ 0.6 ♦️0.4 ♦️  cmd:log VAA s


## Top Right Rotation Resistor
flysky fs-i6xcn|s0|a5 ♦️ in ♦️ -0.7 ♦️-0.5 ♦️  cmd:log VAB nw
flysky fs-i6xcn|s0|a5 ♦️ in ♦️ -0.5 ♦️-0 ♦️  cmd:log VAB ne
flysky fs-i6xcn|s0|a5 ♦️ in ♦️ 0 ♦️0.5 ♦️  cmd:log VAB se
flysky fs-i6xcn|s0|a5 ♦️ in ♦️ 0.5 ♦️-0.7 ♦️  cmd:log VAB sw

## Top Right Rotation Resistor
flysky fs-i6xcn|s0|a5 ♦️ in ♦️ -0.6 ♦️-0.4 ♦️  cmd:log VAB n
flysky fs-i6xcn|s0|a5 ♦️ in ♦️ -0.1 ♦️0.1 ♦️  cmd:log VAB e
flysky fs-i6xcn|s0|a5 ♦️ in ♦️ 0.6 ♦️0.4 ♦️  cmd:log VAB s

## Left Horizontal A3 -0.7 to 0.7 Left- +Right
flysky fs-i6xcn|s0|a3 ♦️ in ♦️ -0.7 ♦️-0.5 ♦️  cmd:log Left Joystick Horizontal Left
flysky fs-i6xcn|s0|a3 ♦️ in ♦️ 0.5 ♦️ 0.7 ♦️  cmd:log  Left Joystick Horizontal Right

## Left Vertical A2 -0.7 to 0.7  Down- +Top
flysky fs-i6xcn|s0|a2 ♦️ in ♦️ -0.7 ♦️-0.5 ♦️  cmd:log  Left Joystick Vertical Down
flysky fs-i6xcn|s0|a2 ♦️ in ♦️ 0.5 ♦️ 0.7 ♦️  cmd:log  Left Joystick Vertical Up

## Left Horizontal A0 -0.7 to 0.7  Left- +Right
flysky fs-i6xcn|s0|a0 ♦️ in ♦️ -0.7 ♦️-0.5 ♦️  cmd:log Right Joystick Horizontal Left
flysky fs-i6xcn|s0|a0 ♦️ in ♦️ 0.5 ♦️ 0.7 ♦️  cmd:log Right Joystick Horizontal Right

## Left Vertical A1 -0.7 to 0.7   Down- +Top
flysky fs-i6xcn|s0|a1 ♦️ in ♦️ -0.7 ♦️-0.5 ♦️  cmd:log Right Joystick Vertical Down
flysky fs-i6xcn|s0|a1 ♦️ in ♦️ 0.5 ♦️ 0.7 ♦️  cmd:log Right Joystick Vertical Up
```
