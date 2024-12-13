# How to Roll up:

## Opening 1st time today
1. open yesterday.
2. Run magic.
3. wait till completion.

## Do you have offline [GREY]
1. get store online
2. still offline ? => leave for later [contact network admin]

## Do you have unbalance [RED]?
1. run ambulance autofix
2. still unbalance? => idk, leave for later [crossover or something]

## Do you have incomplete milking [YELLOW / ORANGE]
1. does store have pending data to milk [Green]?
   1. yes => go to [#3]
   2. no => check and flag for remilk
2. you have lots of stores that need milking today? [if milking them manually takes longer than the next milking cycle]
   1. yes => reload store and leave this for later [milking will bring this in in next hour]
   2. no => go to [#3]
3. is st column less than ho column?
   1. yes => r-click milk direct
   2. no => this could mean HO has extra or store lost its data => leave for later [HO is more than store]
4. wait for completion
5. reload HO [yellow should clear]
6. reload store [green should clear]

## Do you have incomplete rollup [purple]
1. is the incomplete rollup on St column
   1. yes => r-click rollup => Store TransDay
   2. no => go to [#2]
2. Do you have unbalance [RED] or milking todo [YELLOW / ORANGE] that can be fixed ignore offline [GREY] obviously
   1. yes => go fix that 1st
   2. no => sign-off or rollup transday and item gp for the date

## Later  [opening after all above has processed]

## clear offline backlog
1. menu > milking >
2. filter across range offline
3. select 1st of month to yesterday if today is in 1st week of month select from last month to yesterday
4. offline list is too long ?
   1. yes =>
      1. rclick the button [run [x]] below run magic button and run set the value to whatever is stable []
      2. hit [run [x]] and wait.
      3. repeat until you get to end of grid
   2. no => run magic cursor should stop at end of grid
5. refresh grid after you get to the end
6. this list should now decrease to only stores that are currently offline.
7. repeat from [#1] when stores com online

## you left stuff to milk and now need to check if milking happened
1. menu > milking >
2. filter across range needs milking
3. select 1st of month to yesterday if today is in 1st week of month select from last month to yesterday
4. is list too long ?
1. yes =>
      1. rclick the button [run [x]] below run magic button and run set the value to whatever is stable []
      2. hit [run [x]] and wait.
      3. repeat until you get to end of grid
   2. no => run magic cursor should stop at end of grid
5. refresh grid after you get to the end
6. this should have cleared the  Todo columns indicating it milked
7. sort the grid by date.
8. on each unique date Reload Ho. wait for log to show reload complete before doing next date.
9. when you get to the end or after each ho reload refresh grid.

## My plu is not in sync with BO
1. login to rollup
2. open todays date
3. look at stStockOnHand vs HoStockOnHand
4. taking into account the store is still trading and has stuff to milk is this store is out of sync?
   1. yes => is the difference more than 100 units?
      1. yes => r-click > milkdirect > plu all [do you want to delete data at BO?] select yes
      2. no => r->click > milkdirect > plu changes
   2. no => nothing to do
5. comback tommorrow and check the plu counts are closer together or on point.