
~~ BUPPERS ~~
13 T2 engines that propel it at up to 130~m/s unladen
30 cargo crates
one pair of mining laser and ore collector with wiggly script to make them more effective
buncha T2 maneuver thrusters idunno lol, also triangle thrusters for fast cock dodging
ISAN Mono
shoddy but mostly working asteroid avoidance system, it's the green button on the dashboard
	don't worry  that it shows 500 when it's off, it's off, but if it shows anything but 0 while on you better do
	the runny
	the asteroid navigation works by scanning ahead with rangefinders and side-strafing in the opposite direction
	of whatever is in the way, so it isn't particularly clever but it maintains heading
2 extra fuel rods in the back hatch
1 tiny crawlyspace beneath the fuel rods to get to the batteries
2 medium propellant tanks with dedicated propellant syphoning/refueling ports on the sides
	(you have to configure the other ship's resource bridge to have the opposite properties of the one on yours)
	(so, for example: BUP IN: FlowIn 0, FlowOut 1; OTHER SHIP: FlowIn 1, FlowOut 0; then hook them together and 
	watch the fuel leak outta the BUP like sudden onset gonorrhea)
advanced FCU
generator auto-regulation using PID script; "KP" button on dashboard regulates the proportional gain: turn off to 
make the pizza less aggressive
four generators ready to accept an enhancer or something
some extra device hardpoints
enough space topside for at least two somali reacharounds (but beware the green meanie) and one whole big turret, woah

INSTRUCTIONS TO MAKE THIS SHIT WORK, courtesy of some quack:
>>%appdata%\Starbase\ssc\autosave\ship_blueprints
>Save it here and name it ship_whatever number is higher than the last. When you go to load it from autosaves, the name might be blank. Click it.

          ,╓╓╓╓╓╓,,                                          ,╓╓╓╓╓╓,,
       ╓▄▓█████████▒»                                     ,#▓█████████▓m
     |#██████████████░                                   ╓▓█████████████▒,
    |║████████▀▒╚╚▀▀█▌N                                 ╓▓███████▀▀╚╚▒▀▀█▒⌐
    ║███████▒└      ╙▓▓░                               ╔▓██████▒∩      └▒█▒,
   ╠███████▒M       (║█▓∩                            |(▓██████▌∩        ║██▒
  |║███████▓░,      ╔▓██▒                           ||║███████▌░       (╢██▓∩
  |╫█████████▒░╔y╔k▒▓███▒|||      ||||||||||||||||||||║█████████▒╔|,y╔▄▒███▌░
  |║████████████████████▒∩|||||||||||{{{{{{∩||||||||||║█████████████████████░
   ╙████████████████████▒│││⌠⌠││││││░░░░░░│││││││││∩∩∩│▓███████████████████▌∩
    ║██████████████████▌M│││││░░░░╠╠╠╠╠╠╠╠╠╠░░│││││││││╙▀█████████████████▌∩
     ║████████████████▒M││││││╠╠╠╠╠╠╠╠╠╠╠╠╠╠╠╠╠│││││││││╙▀███████████████▌∩
      ╙▀█████████████▒│││││││╠╠╠╠╠╠╠╠╠╠╠╠╠╠╠╠╠╠┤│││││││││╙▀█████████████▀└
       └╙▀█████████▀Ñ││││││││││╠╠╠╠╠╠╠╠╠╠╠╠╠╠╠│││││││││││││║▀█████████▀╙
          └└╙╙╙╙╙└└|└└│││││││││││││││││││││││││││││││││││││││╙╙╙╙╙╙╙└ ||
                  ||||||||||||│││││││││││││││││└└└└│││││||||||||||||||||
                        |||||||||||||||||||||||||||||||||||||||||||||||
                              ||||||||||||||||||||||||||||||||||||||||
               | |                            ||||||||||||||||||||||||
              |||||                                ||| |||||||||(╔∩||||
             ||│║░|                                    |||||||(║▒▒│∩|||
            ||││║▓▒░,,                                ||||||(░▒▓▒▒│∩∩|||
            ||│╠║▒▓▓▓▒▄m╓,,     ~ For Your Health ~ |||||y╔▒▒▓▓▓▓▒░│∩||||
           ||│░╠║▒▒▒▀▀▓▓▓▓▓▓▒▒▒▒▒▒▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▒▒▒▒▓▓▓▓▓▓▓▓▓▓▒░││∩|||
           ||│╠╠╚╚╙││││╙╙╚▒▀▀▀████████████████████████▀▀▀▒╚╙└└└╙╙╚╠││∩|||
           ||└└└||||||    ||||└└└╙╙╙╙╙╙╙╙╙╙╙╙╙╙╙╙╙└└└└||       ||||└└||
                                 |||||||||||||||||||
                                |||||||||||||||||||
                               ||||||{{││││││∩∩∩||
                               ||||||│││││││││||||
                                 ||||||||||||||||
                                   |||||||||||||
