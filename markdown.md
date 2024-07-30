What actions can a user take in my app? 

A. Player can make a game move 
B. New Round 
C. Reset the current game 
D. Toggle menu 


-----------------------------------------------------------


MVC PATTERN 

1. VIEW 
-Add Event Listeners 
- Handle UI-only events 
-Manipulate the DOM 



2. STORE 
-Get State 
-Save State 
-Emit state change event 



3. APP 
-COntorl flow of view and state logic 
-Initialize application 



Video Progression 

1. Naive approach, all in one file 
2. Refactor, iterate as we go 
3. End up with MVC Pattern that is....
a- Easier to debug later 
b- Easier to extedn and add features to later 



-------------------------------------------------------------------------------

Best practices when developing user interfaces 

1. Global scope and namespaces 
2. Stable Selectors (data * attributes)