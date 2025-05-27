# OmenSchema

A collection of JSON Schema definitions for Pathfinder 2E. 

## Overview

This repository contains JSON Schema definitions, hopefully to create easily parsable and editable game content repository for PF2RPG.

## Schema Structure

### Main Schema
- `character-class.schema.json`: Defines the structure for character classes, including required attributes, proficiencies, and skills.

#### Proficiency Types
- `proficiency-rank.schema.json`: Defines proficiency ranks (untrained, trained, expert, master, legendary)
- `armor-proficiency.schema.json`: Defines armor proficiency requirements
- `weapon-proficiency.schema.json`: Defines weapon proficiency requirements
- `skill-proficiency.schema.json`: Defines skill proficiency requirements
- `saving-throw-proficiency.schema.json`: Defines saving throw proficiency requirements

#### Game Mechanics
- `armor.schema.json`: Defines armor categories (light, medium, heavy)
- `weapon.schema.json`: Defines weapon categories (simple, martial, advanced, unarmed)
- `attribute.schema.json`: Defines the six core attributes
- `rarity.schema.json`: Defines rarity levels (common, uncommon, rare, unique)
- `skill.schema.json`: Defines skills and lore categories
- `saving-throw.schema.json`: Defines saving throw types
