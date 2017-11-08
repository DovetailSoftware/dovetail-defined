---
layout: default
title: Dovetail Custom Business Rule Event Creation Times
description: Dovetail Custom Business Rule Event Creation Times
---

# Dovetail Custom Business Rule Event Creation Times

| Name | Path | Object Type  | Comment |
| --- | --- | --- | --- |
| @USERTIME150 | x_next_action_due_date | 0 (case)  | Next Action Due Date for SLA|
| @USERTIME151 | x_imr_due_dt | 0 (case)  | Case Due Date (DMHC) |
| @USERTIME152 | x_med_rec_due_date | 24 (subcase)  | Primary Medical Records Due Date Event Time (DMHC)|

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
