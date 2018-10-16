# Test Case: Plex

## Test Details

* Test Case ID:
  * #3.5Req1
* Test Case Name:
  * Story session pause
* Component: 
  * Play Driver Requirements 
* Test Case Designer:
   * Michael R.
* Creation Date:
  * 2018 October 9
* Modified By:
  * Michael R.
* Modified Date:
  * 2018 October 14
* Requirements Covered:
  * Only works it story mode.
* Test Description/Purpose:
  *  You can’t pause the game in Build (online) mode, its constantly running whether the user is there or not. 
  * To be able to pause the game only in story mode of the game. The user must test the functionality of the pause action and to ensure the game does not continue to run when the function is performed in story mode. Also the user must test to ensure that the pause funtionality does not exist in online mode.
* Pre-Test Conditions:
  * The user's game session currently running and to be able to stop the game momentarily during story mode.
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 | Software starts|Main Menu appears|√ |	
| 2 | User selects Story mode|User is in Story mode |√ |		
| 3 | User may select New Game or Save game|If New game, user is prompted to choose character. If Save game is selected, user chooses their save file and continues the game. |√ |	
| 4 | The player presses "P" key in Story mode| Player pauses game in Story mode |√ |	
| 5 | Player returns to Main Menu| Player exits Story mode and enters game Menu screen|√ |	
| 6 | User selects Build mode|User is in Online mode |√ |			
| 7 |The player presses "P" key in Build mode|Player does not pause game in Build mode |√ |			
| 8 | | | |			
| 9 | | | |			
| 10 | | | |								

## Overall Test Status:
Success


## Run History:

| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 |2018 October 12 |Michael R. |Fail at step 4|			
| 2 | 2018 October 13|Michael R. |Fail at step 7 |			
| 3 |2018 October 14 |Michael R. |Pass |			

## Test Details

* Test Case ID:
  * #3.3Req5
* Test Case Name:
  * #Save game retrieval 
* Component: 
  * Save Game Requirements
* Test Case Designer:
  * Michael R.
* Creation Date:
  * 2018 October 9
* Modified By:
  * 
* Modified Date:
  * 
* Requirements Covered:
  * The file must be saved in a particular format and include all the game data that needs to be read back in at a later time so the game can continue
* Test Description/Purpose:
  * If the file isn’t in a certain format then the game won’t be able to load all the information back in at a later date.
* Pre-Test Conditions:
  * User is able to access the save menu. 
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 |Software loads and Main Menu |The game starts up and the Player is presented with the Main Menu. |√ |			
| 2 |Player selects Story Mode |Story mode Menu appears |√ |			
| 3 |Player selects Load Game |Player goes to the load game Menu |√ |			
| 4 |Player selects their save file | If in the correct format, the player will be able to access their save game |√ |			
| 5 |Save game reading and loading |If read correctly, the save file can properly load with the player's status and previous achievments successfully are stored and obtained |√ |			
| 6 | | | |			
| 7 | | | |			
| 8 | | | |			
| 9 | | | |			
| 10 | | | |			

## Overall Test Status:
Success


## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | | | |			
| 2 | | | |			
| 3 | | | |			

## Test Details

* Test Case ID:
  * #3.3
* Test Case Name:
  * #Req2
* Component: 
  * Save Game
* Test Case Designer:
  * Steven Killen
* Creation Date:
  * Oct. 9, 2018
* Modified By:
  * Michael R.
* Modified Date:
  * Oct. 10, 2018
  * Oct. 12, 2018
* Requirements Covered:
  * The file must be saved in a particular format and include all the game data that needs to be read back in at a later time so the game can continue.
* Test Description/Purpose:
  * Confirm that the save file is saved in its entirety with the proper format, and can later be read from storage.
* Pre-Test Conditions:
  * Save file exists
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 |Load into story mode. |The game will load where last saved. |√ |			
| 2 |Save the game. |The game will save the current state of the game. |√ |			
| 3 |Do things in the game that can be observed, and don't save the game. |These changes will be discarded upon loading a save file.|√ |			
| 4 |Reload the most recent save. |The game will load the most recent save file. |√ |			
| 5 |Exit and reload the game. |The game will return to the main menu. |√ |			
| 6 |Load into story mode. |The game will load the most recent save file. |√ |		

## Overall Test Status:



## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 |Oct. 9, 2018 |Steven Killen |Pass |			
| 2 |Oct. 10, 2018 |Steven Killen |Fail at Step 4 |			
| 3 |Oct 12, 2018 |Steven Killen |Pass |	
| 3 | | | |			
| 4 | | | |			
| 5 | | | |			
| 6 | | | |			
| 7 | | | |			
| 8 | | | |			
| 9 | | | |			
| 10 | | | |			

## Overall Test Status:
Success


