# BGG: Ben's Genode Gems

This is where I put my own Genode apps, servers, libraries, headers, etc. that aren't specifically part of or dependent on BGDE. 

Main branches:  
master - Only tested code should appear in this branch. All files should have proper headers with general information as well as copyright notices, with attribution as necessary. There should be no commented-out code. Code should be divided into commits such that any position in the commit history has complete code with all necessary prerequisites, and has no obvious regressions. Commits will only be added, never deleted or reordered.  
  
staging - Code should meet all the requirements for master, but commits may be modified before being merged into master.  

development - Code should compile and be at least somewhat usable, but may still need changes before being ready to be merged into staging. This allows me to make quick hacks and incomplete components available before they're ready to be merged into staging.  
  
Branch prefixes:  

feature/ - branches for new features/components  

issue/ - branches for fixing issues with code in other branches  

experiment/ - branches for experimental code that may be abandoned or made obsolete  
