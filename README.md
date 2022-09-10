# Grilling a hamburger with a gas grill
Writing my first psuedocode about making a hamburger, V2
## ABOUT
- Hamburgers are grilled ground beef, put between two buns, additional toppings can be placed.
- You can buy preshaped hamburgers or you can shape them with your hands, increasing or decreasing the size.
<br>
- In this first practice we will just do a hamburger with ketchup and mustard, which consist of a preshaped hamburger and two buns and a little ketchup and mustard.
<br>
- Note no ham is needed.
<br>

## Init - getting my *ingredients materials* or variables

### hamburger
- A simple hamburger patty prebought at a store. Will be called hamburgerPatty.
  -  This is what is being grilled and will be necessary for most of the *functions*.

### buns
- plain wheat *buns*, a type of bread bought at a store. Buns are two halves, a top and bottom. Will be called buns.
  - Some people will grill the buns lightly at the end, I hope to add an extra function for this later.
 
### Condiments
- These are additions added to food, to enhance a certain flavor. For this example we will have two called *ketchup* and *mustard*.
  - We will be using packets for each, a packet consist of 9 grams of condiment.

### Gas Grill
- In this example we will use a gas grill. We will call it grill.
  - The grill has parts, which will be defined as gasTank, lid and ignition. This will be defined grillParts [gasTank, lid, ignition]
  - There are various parts

### other
- This will be where we add variables like the plate, and spatula (utensil used to flip the hamburgerPatty)
- We will also add a constant table, which is only referenced as an area to place variables.

### Array
We will make an array, materials[hamburgerPatty, buns, ketchup, mustard, grill, grillParts, spatula, plate].

<br>

## Functions

prepCheck
* check for a spatula, plates gas cannister, gas grill, hamburger patty and buns
* if all there proceed
* else go buy the required materials

prepareBuns
1. Place the plate on an even surface, preferably a table if had but floor is okay as well.
2. Place a pair of hamburger buns on plate, lift the top one off and flip it upside down and place it by the bottom half.
3. Once completed move on.

grillOn
1. Ensure gas cannister is secure and nosel is conncected to the gas grill.
2. Turn the valve on top of the gas cannister towards the open direction shown on the valve.
3. If no sign is on the valve turn the valve toward the left  (counter-clockwise).
4. Move the focus to the grill and click the igniter button. (This usually has a lightning bolt on it)
5. Open the grill top to ensure the flames are going and leave lid open.
6. Allow a few minutes so the grill may heat up.

placePatty
1. Place the patty on the grill using the spatuala.
2. Position the patty towards the center to allow most even grilling.

grilling
1. Grab the grill top's handle and close the grill top.
2. Set a timer for 2 minutes.
3. Once timer rings, grab the grill top handle to open the grill.
4. Move the spatula to under the patty and flip it on the other side.
5. Repeat steps 1-4 until the patty is grilled to your preference, if you like them well done then *gross*

pattyOff
1. Ensure plate with the buns is nearby.
2. Using the spatula, move it under the grilled burger to pick up.
3. Place spatula with burger on it onto bottom bun.
4. Slowly move spatula away leaving grilled burger on bottom bun.
5. Grab the top bun next to the bottom bun and burger, flip it back over and place on the burger.

eat
* Hamburger is complete, eat if you want.

## Running Functions

Run the functions in this order
1. prepCheck
2. prepareBuns
3. grillOn
4. pattyPlace
5. grilling
6. pattyOff
7. eat
8. YAYYYY
