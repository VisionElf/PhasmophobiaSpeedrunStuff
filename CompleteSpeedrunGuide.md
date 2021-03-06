# Complete Guide for Phasmophobia Speedrunning

### By VisionElf

---

# Table of Contents

- [Introduction](#introduction)
- [Ghost Room](#ghost-room)
	- [Ghost sounds](#ghost-sounds)
	- [Room temperature](#room-temperature)
	- [Spirit Box](#spirit-box-room-search)
	- [EMF Reader](#emf-reader-room-search)
	- [Misc](#misc)
- [Evidences](#evidences)
	- [EMF Level 5](#emf-level-5)
	- [Spirit Box](#spirit-box)
	- [Fingerprints](#fingerprints)
	- [Ghost Orb](#ghost-orb)
	- [Ghost Writing](#ghost-writing)
	- [Freezing Temperature](#freezing-temperature)
- [Objectives](#objectives)
	- [EMF Reader Objective](#emf-reader-objective)
	- [Thermometer Objective](#thermometer-objective)
	- [Salt Objective](#salt-objective)
	- [Motion Sensor Objective](#motion-sensor-objective)
	- [Smudge Sticks Objective](#smudge-sticks-objective)
	- [Ghost Event Objective](#ghost-event-objective)
	- [Ghost Photo Objective](#ghost-photo-objective)
	- [Dirty Water Objective](#dirty-water-objective)
	- [Crucifix Objective](#crucifix-objective)
- [Maps](#maps)
- [Ghost Types](#ghost-types)
- [Strategies](#strategies)
- [Advanced Details](#advanced-details)
	- [Ghost States](#ghost-states)

---

## Introduction

Phasmophobia is a game where you need to investigate a haunted building.

There are 4 objectives, 1 mandatory and 3 optionals.

The mandatory objective is to know which ghost type is haunting using provided equipments.

You can see the possible objectives with more details under [Objectives](#objectives).

Each ghost types has 3 evidences and there are 6 different evidences. Check all the evidences with more details under [Evidences](#evidences).

### Speedrun rules

The speedrun rules can be found in the [speedrun.com](https://www.speedrun.com/phasmophobia) website under **View Rules**. The most important ones are:

- You have to **witness** all 3 evidences. Guessing is not allowed.
- All 3 evidences must be seen in one or multiple recordings.

Categories:

**Any%** - You have to witness all 3 evidences and know the ghost type.

**100%** - You have to know the ghost type AND complete all 3 optionals objectives.

**Full Game** - You have to complete all 7 maps in one run.

---

## Ghost Room

The **ghost room**, also known as its **favourite room** is the room where the ghost will have higher probability of wandering in.
Without the ghost room, it is near-impossible to complete objectives and find out which ghost type it is.

In order to find the ghost room, there are multiple elements that can help you.

### Ghost sounds
The ghost sounds are one of the most reliable elements to know which room it is, and it doesn't require any equipment. These sounds includes the following:

1. **Footsteps** (also known as **stomps**) - occurs randomly when the ghost is moving. When the ghost stepped in **salt**, it will create a footstep sound very often for the duration of the **salt**.

2. **Door, light switches and window tapping sounds** - occurs when the ghost interacts, it create level 1 EMF zones -- seen as EMF Level 2 by the **EMF Reader**. It also creates a **Fingerprint** if the ghost has the evidence.

3. **Objects thrown** - occurs when the ghost interacts, it create EMF zones of level 2 -- seen as EMF Level 3 by the **EMF Reader**

4. **Object-specific sounds** - occurs when the ghost interacts with a specific object, like telephones, microwaves, radios etc... it generate a very distinct sound that usually can be heard way more than the others.

In building with more than 1 floor, if the sound has occured in a different floor than where you are, the sound is **muffled** (there is less high frequencies). It is 100% accurate, and can be distinguished with experience.

The sound is **never muffled** if it comes from the same floor as you are, even if there are multiple walls in between.

In all other cases, the sound is spatialized. Meaning that if the ghost is in a room in front of you (even if there are a lot of walls) the sound should come from the middle.

The sound volume will depends on the distance with that sound origin (it will be little when far, and very high when close), and the walls have little to no effects on that volume.

### Room temperature
The most accurate way to see which room is the **ghost room** is using the temperature, that can be detected using a **Thermometer**.

- Every room (except the **Outside** room) starts at temperature **15°C**.

- The temperature starts to drop when the **Main door** is opened.

Every frames, the ghost will lower the temperature of the room its in, by a fixed amount, depending on wether or not the ghost has **Freezing Temperatures** evidence.

- **Freezing Temperature**: **0.12°C** per seconds.
- **Not Freezing**: **0.04°C** per seconds.

The room temperature will **increase** by **0.2°C** per seconds whenever the ghost is not in the room **AND** when **Freezing Temperature** is not an evidence.

The temperature is clamped by a minimum and a maximum, also depending on the **Freezing Temperature** evidence.

- Maximum is **15°C** (starting temperature).

- Minimum is **-10°C** for **Freezing Temperature** and **5°C** for non-freezing.

Because every room starts at **15°C** and never change unless the ghost has walking in it, and because the **Thermometer** has an **error of +/- 2°C**, you can guess which room is the correct one if you see a temperature that is **lower** than **13°C**.

[Here is a graph showing the temperature drops.](https://i.imgur.com/V36iiS0.jpg)

### Spirit Box (Room search)

Because of how it works, the **Spirit Box** can be used to find the ghost room. This can obviously only works when **Spirit Box** is evidence of the current ghost type.

See [Spirit Box](#spirit-box) for more details

**TLDR**

- If you hear something from the **Spirit Box** you're either **in the ghost's favourite room** or **less than 3 meters** away from the ghost.
- The **Spirit Box** will work as long as the **player** in the ghost's range, even if the item itself is not near the ghost.

### EMF Reader (Room search)
### Misc

---

## Evidences

### EMF Level 5

**Associated equipment:** EMF Reader

**Witnessing the evidence:**

- The **EMF Reader** shows an **EMF Level 5** *(all 5 lights are on)*.

**Mechanics**

Whenever the ghost interacts with something or appear, **EMF Zone** are created at the position of the interaction.

- **EMF Zone 1**: Created when the ghost **interacts** with **doors, lightswitches, windows and specific props** *(like telephones)*
- **EMF Zone 2**: Created when the ghost **throw an object**.
- **EMF Zone 3**: Created when the ghost has **appeared** recently.
- **EMF Zone 4**: There is a **33% chance** that an **EMF Zone 1 or 2** will be a **EMF Zone 4** instead, if the ghost has **EMF Level 5** evidence.

The **EMF reader** will reads an EMF Level with the number of the zone + 1.

*Example: EMF Zone 3 is seen as EMF Level 4 by the reader.*

Whenever an EMF Zone is created, the **Total Activity** graph in the truck gets increased by the level of that zone.

If you see an **+4** increased in the graph, you can be sure that it's an **EMF Level 5**, except if:

- A player is/was in the room and said **phrases**, making **multiple interactions** in short amount of time
- The ghost is a **Poltergeist**, and threw **exactly 2 objects** at the **same time**.

Explanations in videos:

- [How to read Total Activity](https://www.youtube.com/watch?v=7Sxcaf-d8bg)
- [Poltergeist Activity](https://www.youtube.com/watch?v=5lwzrqEuUoE)

### Spirit Box

**Associated equipment:** Spirit Box

**Witnessing the evidence:**

- Any sound comes from the **Spirit Box**.

**Mechanics**

Whenever you ask the ghost a question, there are multiple checks.

If any of these checks fail, it will write **NOTHING DETECTED** in the Spirit Box screen.

*Note: if your vocal recognition is not setup correctly, nothing will happen, and that message will not show up.*

The checks are in that order:

1. Player's room and Ghost's current room are **null** *(Basic check in case of bugs)*
2. Player is in the **Outside Room**
3. Player is not in the **same floor level** as the ghost's current room
4. Player is not in the ghost's current room **OR** Player is more than **3 meters** away from the ghost
5. The ghost is **Shy** and there are more than 1 player in the ghost's current room
6. The ghost does not have **Spirit Box** evidence.
7. There is at least one **light** that is turned on in the **player's room**

*Note: ghost's current room is NOT its favourite room, it is simply the room where the ghost is currently in.*

Then there is a random **33% chance** that the response will **fails**, unless you have said the **ghost's first name** in the last **20 seconds**.

*Note: This random check never happens in tutorial.*

As you might have noticed, there is **no checks** on the **Spirit Box** position. Therefore, the **Spirit Box** is not required to be near you or the ghost to be working.

**Spirit Box Questions & Responses**

There 3 type of questions. For each of these question types, you can hear different sounds.

Location sounds can be used to determine ghost's distance from you.

**Location**

*Example: "Where are you?"*

Responses:

*If you are less than 4 meters away from the ghost:*

- [Here](Sounds/SpiritBox/Here.wav)
- [Close](Sounds/SpiritBox/Close.wav)
- [Next](Sounds/SpiritBox/Next.wav)

*If you are more than 4 meters away from the ghost:*

- [Behind](Sounds/SpiritBox/Behind.wav)
- [Away](Sounds/SpiritBox/Away.wav)
- [Far](Sounds/SpiritBox/Far.wav)

**Age**

*Example: "How old are you?"*

Responses:

- [Child](Sounds/SpiritBox/Child.wav)
- [Adult](Sounds/SpiritBox/Adult.wav)
- [Old](Sounds/SpiritBox/Old.wav)

**Difficulty**

*Example: "What do you want?"*

Responses:

- [Death](Sounds/SpiritBox/Death.wav)
- [Kill](Sounds/SpiritBox/Kill.wav)
- [Hurt](Sounds/SpiritBox/Hurt.wav)
- [Hate](Sounds/SpiritBox/Hate.wav)
- [Die](Sounds/SpiritBox/Die.wav)

### Fingerprints

**Associated equipment:** UV flashlight, Photo Camera

**Witnessing the evidence:**

- The **UV Flashlight** reveals a **Fingerprint** on a door, a light switch or a windows.
- Any photo taken by the **Photo Camera** is titled *Fingerprints*.

### Ghost Orb

**Associated equipment:** Video Camera, Head-mounted Camera

**Witnessing the evidence:**

- An **Orb** can be seen through the truck's screen.

**Mechanics**

- The Orb spawns at the beginning of the game, if the ghost has the evidence
- There is only one orb, and it moves randomly around its starting position
- The starting position is random, but it should be near the middle of the room

### Ghost Writing

**Associated equipment:** Ghost Book

**Witnessing the evidence:**

- The **Ghost Book** has writing on it.

**Mechanics**

- When a player says a **Trigger Phrase**, the ghost has a small chance of Writing in the book, if it's in its range
- Any interactable props, including the **Ghost Book** are never removed from the ghost's prop list when they are picked up from the ground, until the prop is thrown or placed on the ground near the ghost
- Therefore, you can place the book in ghost's interaction range, and take the book back to the truck, and the ghost will still be able to interact with it [Example](https://www.youtube.com/watch?v=6lUrclEtxnE)

### Freezing Temperature

**Associated equipment:** Thermometer

**Witnessing the evidence:**

- You're seeing **Cold Breath** inside the room.
- The room temperature is **below 3°C**.
- The room temperature has **dropped very quickly** in a **short amount of time**.

---

## Objectives

In 100% runs, you must complete **all 3 optional objectives** in order to validate the run.

In the following instructions, an **extra equipment** is considered any equipment that doesn't help find the ghost's type evidences.

All the objectives currently in the game, sorted by difficulty:

### EMF Reader Objective

**Find evidence of the paranormal with an EMF Reader**

This is **the easiest objective** you can complete.

The only thing you have to do, is to take the **EMF Reader** and bring it near an **EMF Zone**. Once it shows any level of EMF, the objective is completed.

### Thermometer Objective

**Detect a room below 10 Celsius with a Thermometer**

This can be considered a **very good** OR **very bad** objective depending on the time you're planning to do.

When the ghost has no **Freezing Temperature** evidence, the time it takes for the room to reach **10°C** is around **2 minutes**.

When the ghost has **Freezing Temperature** evidence, the time is reduced to about **40 seconds**.

**Freezing Temperature** is therefore required if you're planning to do a **sub 2 minutes** run with that objective.

The objective is completed when **the room's temperature** has reached **10°C** and when the **Thermometer** has been targeted to that room by any player.

Because it is required to have **the room's temperature** to reach **10°C**, any temperature displayed by the **Thermometer** is **irrelevant**.

Because of the **+/- 2°C Thermometer error** you can only be 100% sure that the room is under **10°C** when your thermometer reaches **7.9°C** (which makes the room temperature up to **9.9°C**).

### Salt Objective

**Get a ghost to walk through salt**

This objective is **very easy** to complete.

However, because it requires an **extra equipment**, it might not be optimal if playing Solo or having too much objectives with **extra equipment**.

Take **Salt** and put up to **3 stacks** in the ghost room or wherever you think the ghost will wander. When the ghost steps in any of these stacks, the objective will complete.

You can be sure that the **Salt** has been stepped on when:

1. the stack has a **visual hole** in it or;
2. you **hear a lot more foosteps than usual** or;
3. the **UV Flashlight** reveal the **Footprints** (*Not applicable for Wraith*)

### Motion Sensor Objective

**Detect a Ghosts presence with a motion sensor**

This objective is **very easy** to complete.

However, because it requires an **extra equipment**, it might not be optimal if playing Solo or having too much objective with **extra equipment**.

Take a **Motion Sensor** and put it on a wall wherever you think the ghost is or will wander. Whenever the ghost pass in front of the sensor, the objectives will complete.

A loud **beep** can be heard from the truck when the ghost or any player pass in front of it, so you can confirm when it's done when you're sure that no player passed it whenever the sound was heard.

### Smudge Sticks Objective

**Cleanse the area near the Ghost using Smudge Sticks**

This objective is **very easy** to complete.

However, because it requires two **extra equipment** --smudge sticks and lighter--, it might not be optimal if playing Solo or Duos and having too much objectives with **extra equipment**.

Take a **Smudge Sticks** and a **Lighter**, and bring it to the ghost's room. Take the **Smudge Sticks** in your hand, and while having the **Lighter** in your inventory, press **F** to light the stick.

Get as close as possible to the ghost to avoid any mistakes, and throw the stick. 

The objective is completed when you light the stick or whenever it ends, if it is less than **6 meters** from the ghost's position.

### Ghost Event Objective

**Have a member of your team witness a Ghost Event**

This objective is heavily affected by **randomness**, making it an **unreliable** objective.

**Ghost Events** are triggered, with a % of chance, whenever the ghost exits its **Idle State**.

The highest the **Activity Multiplier**, the higher the ghost has a chance to trigger a **Ghost Event**.

Except from that, there is currently nothing known that can increases the chance of happening.

There are currently **4** possible **Ghost Events**.

1. All of them will create a **level 3 EMF Zone** -- read as **EMF Level 4** by the reader --
2. Some of them will make the ghost appear for a short and random duration, allowing you to take a **photo of the Ghost** *(see below)*

### Ghost Photo Objective

**Capture a photo of the Ghost**

This objective is heavily affected by **randomness** **AND** requires an **extra equipment**, making it an **unreliable** objective.

It is basically the same as **Ghost Event** *(see above)*, however it requires an **extra equipment**, and has less chance of happening.

### Dirty Water Objective

**Capture a photo of Dirty Water in a sink**

This objective is heavily affected by **randomness** **AND** requires an **extra equipment** **AND** the current map setup, making it a **very unreliable** objective.

The **Dirty Water** objective requires the ghost's **favourite room** to be very close to any room that has a **sink**.

When you find the ghost's room and you're sure that it can reach a **sink**, you can spam **Phrases** to trigger interactions.

These interactions can result in the ghost turning the **sink** on, with **Dirty Water** in it.

Wait a few seconds for the interaction to ends, and take a picture of the sink with a **Photo Camera**.

### Crucifix Objective

**Prevent the Ghost from hunting with a Crucifix**

This objective is heavily affected by **randomness** **AND** requires an **extra equipment** **AND** the current map setup, making it a **very unreliable** objective.

The **Crucifix Objective** almost always requires the **Ouija Board**, because the ghost will never hunt rapidly if all the team has a too high sanity. The only exception is when playing against a **Banshee**, that can hunt before that sanity threshold.

The **Ouija Board** spawns after **10 seconds**.

There is a **50% chance** that the **Ouija Board** will disappear after **10 seconds**.

There is a high chance that the **Ouija Board** will spawn too far away, therefore making it very long to get, and is rarely a good objective that can be completed fast.

When you find the **Ouija Board**, turn it on, and ask multiple times any question, until you get 2 or 3 times the **Ouija Fail** response.

The **Ouija Board** doesn't need to finish its current answer to answer the next one.

When the **Ouija Fail** occurs it will:

1. Flickers the light in the current player's room
2. Turn off the **Ouija Board**
3. Remove **40%** from the player's **sanity**

---

## Maps

[Click here to see the maps images with more informations for each maps. (Ouija Boar spawns and Cameras)](https://imgur.com/a/A4oBdma)

### Tanglewood Street House

##### Possible Rooms

There are **11** rooms.

**First Floor**

- Foyer
- Main Bathroom
- Boy Bedroom
- Nursery
- Living Room
- Master Bedroom
- Kitchen
- Dining Room
- Utility
- Garage

**Basement**

- Basement

##### Tips & Tricks

- You can pass through the wall in the **Garage** to go directly outside using the **Closet Glitch**.

### Edgefield Street House

##### Possible Rooms

There are **16** rooms.

**First floor**

- Hallway
- Living Room
- Kitchen
- Dining Room
- Toilet
- Garage
- Utility

**Second Floor**

- Upstairs Hallway
- Bathroom
- Girls Kid Bedroom
- Girls Teen Bedroom
- Girls Teen Bedroom
- Boys Teen Bedroom
- Boys Teen Bedroom
- Master Bedroom

**Basement**

- Basement

### Ridgeview Road House

##### Possible Rooms

There are **16** rooms.

**First Floor**

- Foyer
- Dining Room
- Living Room
- Kitchen
- Utility
- Toilet
- Hallway
- Garage
- Master Bedroom

**Second Floor**

- Bathroom
- Teen Boys Bedroom
- Boys Bedroom
- Girls Bedroom
- Upstairs Hallway
- Upstairs Toilet

**Basement**

- Basement

##### Tips & Tricks

- **Ridgeview** is one of the only map that has **multiple rooms without any separation** *(doors or walls)*. Because of that, it is often difficult to localize the ghost's **favourite room** if he spawns in that area.
- You can teleport to the truck using the **Closet Glitch** in the **Garage**.

### Grafton Farmhouse

##### Possible Rooms

There are **13** rooms.

**First Floor**

- Foyer
- Living Room
- Dining Room
- Twin Bedroom
- Kitchen
- Master Bedroom
- Utility
- Storage

**Second Floor**

- Upstairs Hallway
- Upstairs Bathroom
- Nursery
- Storage
- Upstairs Bedroom

### Bleasdale Farmhouse

##### Possible Rooms

There are **16** rooms.

**First Floor**

- Foyer
- Office
- Living Room
- Kitchen
- Dining Room
- Toilet
- Hallway
- Garage

**Second Floor**

- Hallway
- Bathroom
- Utility
- Master Bedroom
- Girls Bedroom
- Boys Bedroom
- Side Bathroom

**Attic**

- Attic

### Brownstone Highschool

##### Possible Rooms

There are **58** rooms.

As you will notice, there are multiple rooms that have the same names.

This is not a mistake from me, this is what I found in the old version of the game. It might have been fixed in latest versions.

*Example: 'Classroom 18' is designated as 'Classroom 8' by the Ouija Board*

[Click here to see the full list.](MapRooms/Brownstone_High_School.txt)

##### Tips & Tricks

- The best way to find the room is to listen for **noises**, specifically the **telephones**.
- Although you might found a temperature lower than **13°C** in the corridors because of its movement, the ghost's **favourite room** will never be the corridors.

### Asylum

##### Possible Rooms

There are **120** rooms.

[Click here to see the full list.](MapRooms/Asylum.txt)

---

## Ghost Types

There are currently **12** type of ghosts in the game.

- Spirit
- Wraith
- Phantom
- Poltergeist
- Banshee
- Jinn
- Mare
- Revenant
- Shade
- Demon
- Yurei
- Oni

---

## Strategies

### 100%

#### One-trip Banshee/Wraith

This strategy should be one of the most optimal strategy because it doesn't require any trip to the truck.

However it is very unreliable as the requirements may be painful to get.

**Objectives**

- Restart if any objective requires any extra equipment, except for **Photos**
- Here is the list of the objectives you should look for:
	- EMF
	- Thermometer
	- Ghost Event
	- Ghost Picture
	- Dirty Water

**Items**

- **Thermometer**
- **EMF Reader**
- **UV Flashlight** OR **Photo Camera** *(if you have any photo objective)*
- **SpiritBox** but you leave it in the truck

**Ghosts**

- Banshee
	- EMF 5
	- Fingerprints
	- Freezing Temperature
- Wraith
	- Spirit Box
	- Fingerprints
	- Freezing Temperature

**Description**

Because you should have already all the items with you, no trip to the truck is required, as long as you have the correct ghost (Banshee or Wraith).

### Tutorial

#### Revenant

**Rooms**

- **Foyer**
- **Main Bathroom**
- **Boys Bedroom**
- **Nursery**

**Items**

- **EMF Reader**
- **UV Flashlight**
- **Ghost Book**

**Description**

- Walk into the room, put the **EMF Reader** and **Ghost Book** on the floor
- Trigger the ghost using **Phrases**
- Wait for the ghost to touch a door, and leave a **Fingerprint** AND an **EMF Level 5** at the same time
- Continue spamming and wait for **Ghost Writing**
- Leave the house when you got all three evidences and close the truck

---

## Advanced Details

### Ghost States

There are **25** possible states the ghost can enter.

- **Idle** - The ghost **stands still** and **does nothing**.
- **Wander** - The ghost moves to a random position.
- **Hunting** - The ghost hunts.
- **FavouriteRoom** - The ghost moves to a random position inside its **favourite room**.
- **Light** - The ghost toggles a **Light**
- **Door** - The ghost touch a **Door**
- **Throwing** - The ghost throws an object.
- **Fusebox** - The ghost turns the **Fusebox** off.
- **Appear** - The ghost appears. **THIS STATE DOES NOT COUNT AS GHOST EVENT**
- **DoorKnock** - The ghost knocks on a **Door**.
- **WindowKnock** - The ghost knocks on a **Window**.
- **CarAlarm** - The ghost interacts with a **Car**.
- **Radio** - The ghost interacts with a **Radio**
- **Flicker** - The ghost **flickers** the lights.
- **Cctv** - The ghost turns a **Video Camera** off.
- **RandomEvent** - The ghost does a random **Ghost Event**.
- **GhostAbility** - The ghost executes its **Ability** *(For these ghosts: Wraith, Phantom, Poltergeist, Banshee, Jinn)*
- **KillPlayer** - The ghost kills a player.
- **Sink** - The ghost create **Dirty Water** in a sink.
- **Painting** - The ghost drops a **Painting** from the wall.
- **LockDoor** - The ghost locks a door. *(The ones you can find their keys)*
- **Mannequin** - The ghost interacts with a **Mannequin**.
- **Sound** - The ghost plays a sound from an object. *(Not sure if used in the game)*
- **AnimationObject** - The ghost plays an animation from an object. *(Not sure if used in the game)*
- **TeleportObject** - The ghost teleports an object. *(Not sure if used in the game)*