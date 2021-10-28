# Project-To-Do-Game
## Аplication description
The idea of application is to make to-do-lists that will work as tamagachi game.
## Roles
	Admin
	User
	Guest
## Parts
	Lists
		name
		description
	Tasks
		name
		descrition
		list name
		deadline
		done/not(maybe)
	Tamagachi
		Helth
		Money
		Hill
		Status: helthy, ill, dead.
At the begining tamagachi will have 100 hp, 0 coins, status helthy, hill will cost 15 coins and return 10 hp.
## Actions of user
 1. Program will have register form were user mast enter:
  UserName,
  Password
	and click button "Enter", that will close form and show main page with tamagachi and lists. Program will generate id for user and add user to database.
 2. Program will have log in form were user mast enter:
  UserName,
  Password
	and click button "Enter", that will close form and show main page with tamagachi and lists.
 3. Click button "Add list" and get form were user must add name of the list and optionaly can add description of the list and accept changes.
User will see added list in list of lists with description. If description will be big user will see only part of it. Information about list will be add to database.
 4. Click button "Add task" and get form were user must add name and deadline of the task and optionaly can add description of the task and accept changes.
User will see added task in the list with deadline and description that will work as it was mantioned earlier. Information about task will be added to database(DB)
 5. User can click on task(list) and get information about task(list), delete task(list), change tasks(lists) name or description or deadline and accept changes. 
Information about task(list) will be changed in database
 6. User close forms from 2-4 par. without changes.
 7. User can mark task as done before deadline. Task will be deleted. Tamagachi will earn 1 coin. info in DB will be changed (or task can be marked as done in DB and user can choose
delete it or not P.S. Don't know what is better).
 8. User don't mark task as done before deadline.Program will ask for time every time user enters system and check deadlines of not done taks. If deadline was skiped, program will
ask about task using form "Have you done this tasks?" and then there will be list of tasks that user can mark as done, but if user don't mark task as done, task will stay in DB and
tamagachi will loose 3 hp.
 9. User can allow another user to be his or her guest, using form where user can click button add guest and find user using username or id.
## Actions of guest
 1. Guest can't change anything in lists and tasks of other person. Guest only can see what isn't marked as done, helth, status and number of coins of tamagachi.
 2. Guest can help user with coins or buying hilling if user is close to deth using form(if user have 20 hp or less). Guest will lose donated coins. User will get hill or coins depending on what
guest have chosen.
## Admin
 1. Can see statistics: number of users, number of dead, number of ill, number of healthy, ban people, helth and money of one person.
 2. Help users by giving them presents (coins) to moderate difficulty.
 3. Ban users.
## Tamagachi status
	1. Healthy (100-40hp):
   		Hill -15 coins + 10hp
	2. Ill(40-1hp):
		Hill -10 coins + 15hp
		After 20hp guest help
 	3. Dead (0hp):
		User can't change tasks and lists and mark them as done for 24 hours of tamagachi hill

## P.s. what can be added (if will be enough time to do this)
	Calendars
	Other thingth to shop not only hilling
	Dayly habit tracking
	More statistics for user or guest (and for the admin obviously)
	Task difficulty
	More ways for admin to modedrate difficulty.
I macket in process of thinking, tabels of DB in progress of thinking 
     