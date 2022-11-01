# TimeSheet_Macro
This was made during my tour as a Marine service engineer (2013) to clock the hours spend onboard for repair/retrofit/commission/survey jobs. 
This tool will auto compute the hours for the 1.25, 1.5 and 2 OT respectively.
Allows ease of inputting details with drop down list.
Saves 90% of the time compare to manual method and also achieve human error free.
=================================================================================

'Created 25/04/2013 by Lam CS
'User notes:
'       - This will allow user to key in their working hours on normal weekdays and in return auto calculate
'       the total hrs for OT A / B and normal office hrs.
'       - This will not auto calculate the hrs for days that fall on weekends and public holidays.


'Modified 29/4/2013
'   - Add the function mainly for Oversea jobs that has certain rules that will deem the claims to be OT or Oversea rates.


'Modified 8/5/2013 (REV3)
'   - Add the drop down list for hrs, Tank, Oversea, In progress.
'   - fix the bug for the checking of first time entry
'   - added the function for self checking after completing macro for -ve hrs and name and date

'Modified 22/5/2013 (REV3.1)
'Fixed format issues and alighment
'

'Modified Jun/2013 (Rev3.2)
'Bigger Fronts for Admin

'Modified 25/Jul/2013 (Rev3.3)
'   - bug fix for checking if OTA PM hrs need to calculate.
'   - add in round up Function to 1 dec place for all hrs (X.X hrs).

'Modified 25/Jul/2013 (Rev3.31)
'Bug fix for -0.0000000000001xxx probs

