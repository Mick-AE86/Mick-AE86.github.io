## Bug Examination within Fallout 76

### Issue 1 
###### (Acquired from https://www.reddit.com/r/fo76/comments/a1to3g/december_4th_patch_notes/)
#### Stabilitiy and performance issue: Console: The player could encounter an infinite loading screen when signing out of their console account while playing Fallout 76.
Type of testing: White box, Compatibility Testing. Perhaps the code they implemented to sign someone out of an account linked to a computer may not work as intended when signed out of a console. The developers would have to fix and test the procedure in different environments. 
### Issue 2
#### User Interface: Respawn: Players who die while severely overencumbered will have all map markers removed when attempting to respawn. The player would have to restart at the original start point after respawning.
Type of testing: Black Box, Acceptance testing. The player wouldn't want to have the inconvenience of having their markers removed over a death. Testing to meet the requirements and convenience for the consumer is my reason for choosing this testing method.
### Issue 3
#### User Interface: Enemies: Red crosshairs and enemy health bars stay on-screen when an enemy is not in sight.
Type of testing: Black box, Functional testing. The enemy health bars shouldn't be on screen if the enemy is not in the player's field of view. Testing to make sure that the appearence of health bars behaves as intended could have posibly prevented this from occuring. 
### Issue 4 
###### (Acquired from https://www.reddit.com/r/fo76/comments/a2wci6/psa_if_you_see_a_gulper_storing_a_ton_of_missiles/)
#### Stash: Phantom weight may be acquired due to looting gulpers with 44 missles. The player cannot rid themselves of the weight even if their stash is empty.
Type of testing: Black box, Functional (maybe negative too?) and acceptance testing. The user shouldn't have to deal with extra weight to carry around when they have nothing in their inventory. That should have been a minmum criteria, and perhaps testing for this instance can help with creating a patch that makes sure acquiring the items behaves as it should without creating phantom weight.
### Issue 5
###### (Acquired from: https://twitter.com/y_nakajima_/status/1069111762610356224)
#### Stability and performance issue: In the Whitespring Resort area, there seems to be a bug occuring where many robots are being generated.
Type of testing: White box, Functional. The developers would have to test the code that spawns the robot and figure out how they could prevent the code from spawning multiple of an asset and behave correctly.
