# acronymmap
Read in a paragraph and replace each acronym with the group of words it represents.


Here the list of acronyms and matching phrases :

TSO – Texas State Optical
PDA – Personal Display of Affection
RBI – Runs Batted In
SO – Strike Out
FG – Field Goal
CPU – Central Processing Unit
HD – Hard Drive
PU – Pick Up



Sample Data : 
8
TSO - Texas State Optical
PDA - Personal Display of Affection
RBI - Runs Batted In
SO - Strike Out
FG - Field Goal
CPU - Central Processing Unit
HD - Hard Drive
PU - Pick Up
I drove my PU to TSO to get a HD.  My 
CPU has a virus.  I sometimes SO 
when trying to kick a FG.  I had 2 RBI
at the game.  I saw 2 PDA 
infractions in the hall.  



Sample Output :


====    MAP CONTENTS    ====


{CPU=Central Processing Unit
 FG=Field Goal
 HD=Hard Drive
 PDA=Personal Display of Affection
 PU=Pick Up
 RBI=Runs Batted In
 SO=Strike Out
 TSO=Texas State Optical}



====    READ LINES      ====


I drove my Pick Up to Texas State Optical to get a Hard Drive. My
Central Processing Unit has a virus. I sometimes Strike Out
when trying to kick a Field Goal. I had 2 Runs Batted In
at the game. I saw 2 Personal Display of Affection
infractions in the hall.
