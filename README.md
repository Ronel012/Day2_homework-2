# Day2_homework-2
Create an application with the following speciﬁcations
-The application must be able to edit a value in the cell, cell index must be
supplied by the user
-The application must allow the user to choose to edit either key and/or value
Example: Edit: 0x0 - key
New Value: eee
  eee,fda !!!,1fa Sdc,66s
  ddd,?/1 c@#,;”a ><.,5qa
  /~`,tt2 40O,8gg f][,><a
  
 -The application must be able to print the values in the table
 -The application must be able to reset the table, the application will restart by
  asking the user to input new table dimensions.
  - The application must be able to sort rows (ascending or descending order
  deﬁned by the user) by combining the key and value values’ of the cell then
  compare it to its neighbors
  
  -The application must be able to sort rows (ascending or descending order
  deﬁned by the user) by combining the key and value values’ of the cell then
  compare it to its neighbors
  eee,fda !!!,1fa Sdc,66s   !!!,1fa Sdc,66s eee,fda
  zzz,bbb zzz,aaa yyy,bbb   yyy,bbb zzz,aaa zzz,bbb
  -The application must be able to add columns dynamically by identifying which
  row to add speciﬁed column (example below identiﬁes user is adding an
  additional value on row 0) 
  eee,fda !!!,1fa Sdc,66s   !!!,1fa Sdc,66s eee,fda qqq,bbb
  zzz,bbb zzz,aaa yyy,bbb   yyy,bbb zzz,aaa zzz,bbb null/non-existent
  - Table should be persisted on a text ﬁle from which the application can read on startup to recover current table state
