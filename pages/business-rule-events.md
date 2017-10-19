---
layout: default
title: Business Rule Events
description: Custom Business Rule Events created by Dovetail
---

# Business Rule Events

| Rule ID/Range  | Application  | Comment |
| --- | --- | --- | 
| USER1005 | Agent 5 | Run Task Set - Task Manager
| USER1006 | Agent 11 | SLA - Next Action Due Date Calculated
| USER1007 | Agent 11+ | Change Severity
| USER1008 | Agent 16 | Reopen Action Item
| USER1009 | | Change Case Type (used in DMHC-agent)
| USER1010 | | Primary Medical Record Received (used in DMHC-agent)
| USER2500-USER2525 | SCI  | Source control operations|
| USER2530-USER2539 | RPA  | Page request and response|
| USER2550-USER2565| PO module  | Purchase Order operations|


### Example DAT file
```
/* Business Rule Event - used by Business Rule page in Dovetail Admin (version 3.6+)*/
OBJECT  TYPE="config_itm", NAME="Next Action Due Date Calculated"
  UNIQUE_FIELD = name
  FIELDS
   name ="Next Action Due Date Calculated";
   description="Dovetail - SLA - Next Action Due Date Calculated";
   value_type = 1001;
   i_value = 1006;
   str_value="CASE";
  END_FIELDS
END_OBJECT  NAME="Next Action Due Date Calculated"
```
