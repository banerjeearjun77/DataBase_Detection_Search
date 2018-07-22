# DataBase_Detection_Search

The goal of this startup project is to create a structure that can 
  1. Detect if an attacker is close to inferring a verifiable pattern of transactions a user stored in the database makes
  2. Suppress information that can lead to a verifiable, non-ambiguous inference.
  
The ultimate goal of this project is to ensure that a database can remain private by not giving away enough information to an attacker for him/her to make successful inferences about transaction patterns of a user. 

General Steps:
  1. While all relations are part of the database, we will treat them as disjoint objects known as "blocks" or "nodes" in order to keep track of information accessed by an attacker.
  2. We will generate inferences from the attacker's perspective so that we can compare how likely it relates to inferences generated by the overal database.
  3. Create a fast, scalable version of inference comparison and modification that can handle the addition of new relations. (A problem I do not have in mind on how to tackle, but I'm sure I can get over this technical challenge easily enough once we get there :) )
