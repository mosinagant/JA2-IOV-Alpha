JA2_IoV_929_b2
=============
Adapt IOV to JA2-1.13 Project
-----------


**FAQs:**
=============
1. How to use these files?
-----------
Ans: Copy all files directly into the latest Ja2_1.13 revision's root directory. You don't need to modify Ja2.ini or VFS conf. files unless you want to play with other Maps. Do not modify ITEM_SIZE or WEAPON_SIZE value in the Data-IOV/Ja2_options.ini.

PS: Files/Directories start with ".git" are not needed for Ja2_1.13 game, you can delete them if you downloaded this package. It is needed if you use Github client to keep track with the latest revision.

2. How to use the Xml_Editor:
-----------
Ans: Copy all missing files from Data-1.13 dirctory into Data-IoV directory (!Important: DO NOT overwrite). Run XML_Editor_for_IoV.exe.

**Bugs still under troubleshooting:**
-----------
1. Certain size of magazines are not recognized when the game automatically assigns these magazines to a weapon, this will cause the weapon and magazines to disappear.

Fix Logs:
-----------
**Commit 14 (BugFix No.4)**

1. Change Item.Index.299 "Utility Knife" ItemSize to 27 so it can be fit into body knife slot.

2. Change MOLLE II pouches ItemSize to 49/50/58/59 so it can be fit into MOLLE II Vests.

3. Delete IoV929beta.7z package.

4. Update README.md.

**Commit 13 (BugFix No.3)**

Fixed: Duplicate magazine index in Magazines.xml, 4.7mm 255rnds Index-364 now moved to Index-879, all 4.7mm mags are bug free now.

Fixed: Wrong pics for Simple LAM on/off in Items.xml, index-1853 and index-2655 now using P1item335.sti, the same as FlashLight index-876.

Updated: Update Ja2_options.ini for latest 1.13 revision.

**Commit 12 (BugFix No.2)**

1. Fix Missing starting weapon for BOSS, weapon changed.

2. Fix attachment type for FL handguard. Add ON/OFF info.

**Commit 8-11 (BugFix No.1)**

BugFix: Fixed conflicting indexes.

Upload: Xml_Editor_for_IoV.

Update: Radio Operator features adapted.

**Commit 7**

Update ini files for IoV mod.

**Commit 1-6**

Upload IoV_929_beta files.