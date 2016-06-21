---
layout: default
title: Dovetail Custom Business Rule Event Creation Times
description: Dovetail Custom Business Rule Event Creation Times
---

# Dovetail Custom Business Rule Event Creation Times

| Name | Path | Object Type  | Comment |
| --- | --- | --- | --- |
| @USERTIME150 | x_next_action_due_date | 0 (case)  | Next Action Due Date for SLA|

### Example DAT file:
```
OBJECT  TYPE="prop_name", NAME=Next_Action_Due_Date
 UNIQUE_FIELD=obj_type, prop_name
  FIELDS
   obj_type=0;
   prop_name ="@USERTIME150";
   path_name="x_next_action_due_date";
   val_type=609;
   max_len=30;
   extra_info = "Next Action Due Date";
  END_FIELDS
END_OBJECT  NAME=Next_Action_Due_Date 
```
