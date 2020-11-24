# redm_theatre 🎬
Theatre shows for [RedM](https://redm.gg/)!

## Table of Contents
- [Preview](#preview)
- [Commands](#commands)
- [Exports](#exports)
- [Available shows](#available-shows)
- [Available movies](#available-movies)
- [Available towns](#available-towns)
- [Supported frameworks](#supported-frameworks)

## Preview
- [Cancan](https://streamable.com/6i8rnq)
- [Fire Breather](https://streamable.com/qyv9v8)
- [Josiah Blackwater Story](https://streamable.com/dsrt8s)

# Commands
- `/startshow showName`, to immediately start show.
- `/startshow movieName townName`, to immediately start movie in town.
- `/scheduleshow showName hour minute day`, to schedule a show, day is optional argument.
- `/scheduleshow movieName townName hour minute day`, to schedule a movie, day is optional argument.

## Exports
- `exports["redm_theatre"]:StartShow(showName)` to start a local show.
- `exports["redm_theatre"]:StartShow("MOVIE", townName, movieName)` to start a local movie.

## Available shows
- BIGBAND_A
- BIGBAND_B
- BULLETCATCH
- CANCAN_A
- CANCAN_B
- ESCAPEARTIST
- ESCAPENOOSE
- FIREBREATH
- FIREDANCE_A
- FIREDANCE_B
- FLEXFIGHT
- ODDFELLOWS
- SNAKEDANCE_A
- SNAKEDANCE_B
- STRONGWOMAN
- SWORDDANCE

## Available movies
- BEAR
- JOSIAH
- SECRET_OF_MANFLIGHT
- SAVIORS_AND_SAVAGES
- GHOST_STORY
- DIRECT_CURRENT_DAMNATION
- FARMERS_DAUGHTER
- MODERN_MEDICINE
- WORLDS_STRONGEST_MAN
- SKETCHING_FOR_SWEETHEART
- BEAR_TENT
- JOSIAH_TENT
- SECRET_OF_MANFLIGHT_TENT
- SAVIORS_AND_SAVAGES_TENT
- GHOST_STORY_TENT

## Available towns
- SAINTDENIS
- VALENTINE
- BLACKWATER
  
## Supported frameworks
Basically, script is not compatible with any public framework as RedEM or VORP (you need to adapt it by yourself).