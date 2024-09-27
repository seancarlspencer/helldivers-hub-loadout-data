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
- New additions must always go on the bottom of their respective lists
- Universal Formatting
  - **name:** String simplified name of the item/stratagem, etc. E.g. "Machine Gun"
  - **descriptive-name:** String full name of item.  E.g. "MG-43 Machine Gun"
  - **stats:** Object containing any number of key value pairs.  The key is the String name of the stat.  The value is the Integer value of the stat.
  - **traits:** String with comma-separated values for any number of traits.
  - **price:** Integer price as it appears on that page of the warbond for that corresponding currency.
  - **warbond:** String name of the Warbond where this item is located.
  - **page:** Integer representing the page of the Warbond within which this item is found
  - **level:** Integer representing unlock level
  - **premium:** Boolean indicating whether or not this is locked behind a premium warbond.

### Primary Weaponry

```json
{
  "name": "FLAM-66 Torcher",
  "description": "",
  "category": "primary",
  "sub-category": "Special",
  "stats": { "damage": 250, "capacity": 80, "recoil": 3 },
  "traits": "Medium Armor Penetrating,Incendiary",
  "price": 40,
  "warbond": "Freedom's Flame",
  "premium": true,
  "page": 2
}
```
