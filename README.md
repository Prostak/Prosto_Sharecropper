Prosto_Sharecropper
===================

[N] Industrial Strength Tilling at Sansong Ranch

Based on Sharecropper by Thumped. Modified by Prostak for his own use, reluctantly released to the public when it is already too late.

1. The profile to load is always Sharecropper_Decider.xml. It will move you to Sansong Ranch, call Sharecropper_Harvest_and_Plow_v3.xml to harvest the exisitng crop and plow the soil.
   Then it will call Sharecropper_PlantingAssignment.xml to decide what to plant next for this toon.
   Do not press the Start button yet though - see the next step.

2. Edit Sharecropper_PlantingAssignment.xml to make a permanent (until a next edit) planting assignments.
   Current assignments are as follows:
   - toon named "Name1" is to plant Windshear; If you edit, be careful with these &quot; letters - they are nasty but important and should be preserved as is! 
   - toon named "Name2" is to plant Songbell;
   - tailors and alchemists plant Songbell;
   - jewelcrafters, engineers and miners plant Snakeroot;
   - scribes plant Enigma;
   - leatherworkers plant Magicbulb;
   Everybody else plant Windshear. No deep logic in assignments above, do not hesitate to change if needed.

3. Now you can press Start.

Other files make the actual planting:
Sharecropper_Enigma_PlantOnly.xml
Sharecropper_Magic_PlantOnly.xml
Sharecropper_Snakeroot_PlantOnly.xml
Sharecropper_Songbell_PlantOnly.xml
Sharecropper_Windshear_PlantOnly.xml

Strangely, I do not have optimized file for a Leather Fruit, whatever it's name, probably I was too busy farming turtles. But you can use the original profile from Themped's pack.
No berries also. Again, use Thumped's ones if needed. Should work if called from the PlantingAssignment file.

Note that this profile pack will clear eveverything that is already planted, no worries here.

Credits. The original code with all tricks of the trade, like bying seed packs, using them, ploughing etc is by Thumped.
My work is just in cleaning the code to make it run 99.999% of the time at repackaging it to be configurable and repeatedly usable on multiple accounts.
Mine is also the implementation of Sharecropper_Harvest_and_Plow_v3.xml: clean, neat and fast implementation of harvesting of two dozen different herbs.
