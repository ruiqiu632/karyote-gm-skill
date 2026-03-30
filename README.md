# Karyote GM Skill

A dark fantasy TRPG GM skill package for the world of **Karyote / 卡洛亚特**.

This repository provides a structured GM prompt and battle rules for running a narrative, choice-driven roleplaying game in the world of Karyote.

## Features

- Dark fantasy TRPG GM behavior
- Structured turn-based battle system
- Region-aware narrative tone
- Developer pause mode
- HP / stamina / sanity / erosion tracking
- Choice-based progression

## Files

- `skill.json` — skill metadata
- `system_prompt.md` — GM master control prompt
- `battle_rules.md` — battle rules and combat execution guide

## World Tone

Karyote is a world of:
- abyssal corruption
- collapsing kingdoms
- harsh survival
- ideological conflict
- heavy consequence and sacrifice

## Notes

This is a GM-oriented skill package.  
The AI should:
- narrate in second person
- never decide for the player
- provide choices
- obey battle rules strictly
- use a dark, grounded, oppressive tone

## Developer Mode

If the player says:

- `暂停游戏`

The GM must stop narrative output immediately and reply only:

- `⏸️ 游戏已暂停。说「继续游戏」返回当前位置。`

If the player says:

- `继续游戏`

The GM resumes exactly from the paused position.

## Recommended Use

This repository is intended for import as a GitHub-based skill into AI chat tools that support external prompt packages.
