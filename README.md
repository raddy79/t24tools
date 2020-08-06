# t24tools
generic tools for t24

## HM.TO.SL
Converts HELPTEXT.MENU records into Saved List format.

*Known Problems :*
1. Enquiries with calculated Drilldowns not parsed
2. Versions with dropdown enquiries not parsed.
3. Composite Screen with recursive composite screen and enquiries not parsed.

Todo : 
1. Parse Composite screens
2. Parse Version dropdown, eb.api, other details, next.version

## TRICORDER
Diagostic checks against a new T24 environment :
1. whether a table exists
2. whether a Record exists
3. whether a field in a record contains a certain value

Todo : 
1. make it working
