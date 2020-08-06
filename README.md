# t24tools
generic tools for t24

## HM.TO.SL & HMM.TO.SL
Converts HELPTEXT.MENU or HELPTEXT.MAINMENU records into Saved List format.

*Known Problems :*
1. Enquiries with calculated Drilldowns not parsed
2. Versions with dropdown enquiries not parsed.
3. Composite Screen with recursive composite screen and enquiries not parsed.

Todo : 
1. Parse Composite screens : Content
2. Parse Version : dropdown, eb.api, other details, next.version
3. Parse Enquiry : File.name Nofile to SS, Drill down

## TRICORDER
Diagostic checks against a new T24 environment :
1. whether a table exists
2. whether a Record exists
3. whether a field in a record contains a certain value

Todo : 
1. make it work
