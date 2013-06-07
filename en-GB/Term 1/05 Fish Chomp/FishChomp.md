Level 2

#Fish Chomp

__Introduction:__

__Let’s make the Hungry Fish swim around the sea!__


```scratch

		point towards mouse-pointer
		move 3 steps
	(end forever)
```
Move the mouse pointer around the sea. Does the fish follow the pointer?



		point towards mouse-pointer
		move 3 steps
	(end forever)
```



##Things to try


1. Create a new sprite from the file animals/lobster1. 
2. Use the Shrink sprite tool (above the Stage)

```scratch

		move 2 steps
		turn pick random -20 to 20 degrees
		if on edge, bounce
	(end forever)
```

###Test Your Project





		move 2 steps
		turn pick random -20 to 20 degrees
		if on edge, bounce
		if touching Hungry Fish?
			hide
			wait 3 secs
			show
		(end if)
	(end forever)
```

###Test Your Project

2. How could we make sure the prey only disappears if it is touching the hungry fish’s mouth? Well, we could use the touching color block, and see if it is touching the fish’s blue teeth. To do this, replace the touching block with a

		move 2 steps
		turn pick random -20 to 20 degrees
		if on edge, bounce
		if touching colour []?
			hide
			wait 3 secs
			go to x:random -220 to 220 y: pick random -170 to 170
			show
		(end if)
	(end forever)
```


4. The fish needs to know when it has eaten something so it can play a sound and change its skin. To do this, we can have the prey broadcast the fact that it’s been eaten before vanishing.

```scratch

		move 2 steps
		turn pick random -20 to 20 degrees
		if on edge, bounce
		if touching colour []?
			broadcast got me
			hide
			wait 3 secs
			go to x:random -220 to 220 y: pick random -170 to 170
			show
		(end if)
	(end forever)
```

6. Then, add a new script to the Hungry Fish to respond to the message broadcast by the prey. This script should make the fish play the 'chomp' sound and switch to the mouth-closed costume, wait briefly and then switch back.

```scratch

```

__Now our Hungry Fish is ready to eat, let’s fill the ocean with prey. Right-click on the prey sprite and click “duplicate” several times.__

###Test Your Project

Save your project

###Things to think about












###Test Your Project







