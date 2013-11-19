JA2-IOV-Alpha (Please feel free to edit and post advice.)
=============

Adapt IOV to JA2-1.13 Project

Project's detailed plan:


Step 1. Rework item.xml for 1.13 item system.

1-1: Adding upto 6600 new emply ItemIndex in prepare for future 1.13 updates, 
so that IOV will have full 1.13 items and no need to independently modify other 
linked .xml files in the future (only to sync and add). (Finished)

1-2: Cutting IOV item.xml into two parts, head already has original items reservoir (some are modified and added)
move the tail to Index 3661+. (Finished)

1-3: Compare the head part, reverse 1.13 feature so we can adapt 1.13 .xml system perfectly 
without modifing anything that already exist. The different/added item will be moved to the tail part.


Step 2. Round out new item.xml attributes to reduce possible future bugs.

Step 3. Add elements for IOV specific items in the .xml system.

Step 4. Pick obvious bugs.

Step 5. Inner test.
