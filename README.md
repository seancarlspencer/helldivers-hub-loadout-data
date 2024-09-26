# Helldivers Hub Loadout Data
---
## Purpose

Keep up-to-date stats and item for Helldivers-Hub.com and any other site that wishes to utilizes this information.
---
## Categories
```
Primary Weaponry
Secondary Weaponry
Armor Passives
Armor Types
Grenades
Stratagems
Boosters
Ship Modules (Not in use)
```
---
## Formatting Guide

Each Category has their own formatting of how to structure each Object.  Improvements and adjustments are welcome as considerations, but may not be implemented (on the site) until the website accounts for these adjustments.

### Overarching rules

- Infinity is usually represented by "-1"

### Primary Weaponry

```json
{
    "name": "Gun Name", //String
    "description": "", //String
    "category": "primary", //String. always primary
    "sub-category": "Gun Type (Special, Shotgun, etc.)", //String
    "stats": { "damage": 999, "capacity": 999, "recoil": 999 }, //Object of String : Integer
    "traits": "Comma-separated traits, e.g. Medium Armor Penetrating,Incendiary",
    "price": 40, //Integer
    "warbond": "Freedom's Flame", //String
    "premium": true, //Boolean
    "page": 2 //Integer
}
```
