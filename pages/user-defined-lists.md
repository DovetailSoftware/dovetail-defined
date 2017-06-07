---
layout: default
title: Dovetail Custom User-defined Lists
description: Custom User-defined Lists created by Dovetail
---

# Dovetail Custom User-defined Lists

| List Name | Application | intval1 | Comment |
| --- | --- | --- | --- |
| RQST Part Selector Type | Agent (v8) | 1000 | Part Requests - Select Part From|
| Task Action | Agent (v10)  | 1001 | Task Manager|
| Task Status | Agent (v10)  | 1002 | Task Manager|
| Task Data Type | Agent (v10)  | 1003 | Task Manager|
| Create Subcase Params | Agent (v10)  | 1004 | Task Manager|
| Create Action Item Params | Agent  | 1005 | Task Manager|
| Canned Response Availability | Agent (v11) | 1006 | Canned Responses feature|
| Canned Response Object Type | Agent (v11) | 1007 | Canned Responses feature|
| Dovetail Feedback Subject | Agent (v16) | 1008 | Submit feedback fuctionlity|
| Auto-Dest Operations | Agent (v17) | 1009 | Auto Dest operations|
| Themes | Agent (v18) | 1010 | Agent Theme Options|

---

#### what is intval1 and why is it used here?

`intval1` is a trick/hack that allows for setting uniqueness of a hgbst_elm within a DAT file. this allows for importing the same DAT file multiple times, and doing an update on a hgbst_elm (if it exists). without this, everytime we import a DAT file, we would get new hgbst_elm records inserted, which is not what we want.

#### Example

~~~
OBJECT TYPE="hgbst_elm", NAME="hgbst_elm1"
UNIQUE_FIELD=title,intval1
  FIELDS
    title = "Active";
    state = "Default";
    rank=0;
    intval1=1002;
  END_FIELDS
  RELATIONS
    TO_NAME="hgbst_show1" REL="hgbst_elm2hgbst_show";
  END_RELATIONS
END_OBJECT NAME="hgbst_elm1"
~~~
