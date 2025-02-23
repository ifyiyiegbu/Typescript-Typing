# Typescript-Typing

A sample code was given. [click here](https://docs.google.com/document/d/1wI-IJcXLkwh6IL6zpLGk9OvQR2ueqapGasyv5jVaTJE/edit?tab=t.0).

The task is to:

Fix the typings for the filterPersons function so that:

It returns User[] when personType is 'user'.
It returns Admin[] when personType is 'admin'.
The function should accept partial User or Admin types based on the personType argument. For example:

If personType is 'user', the criteria argument should accept a partial User object.
If personType is 'admin', the criteria argument should accept a partial Admin object.
The criteria object should exclude the type field (i.e., you should not allow filtering by the type property).
