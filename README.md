
# WaifuBot (0.0.1-beta)
Made in China version of Mudae bot's Waifu rolling. Currently being rewritten.

## Database files
Database json files area available [here](https://github.com/Moistbobo/Bobo-waifubot-db)

## Current features
- Adding waifu through valid json documents in discord
- Waifu Gacha
- Server based claiming
- vndb integration (query vndb for additional information on vn type series)

## Requirements
- [NodeJS](https://nodejs.org/en/)
- [Typescript](https://www.typescriptlang.org/#download-links)
- [MongoDB](https://www.mongodb.com/download-center/community)
- **Optional**: [Robo3t](https://robomongo.org/download) 

## Getting started
1. Ensure requirements are installed
2. Clone the repo (develop branch)
3. `npm i`
4. Copy the `env.sample` as `.env` and fill out the `BOT_TOKEN` and `BOT_PREFIX` fields. By default, `BOT_PREFIX` is set to `.`
5. `npm run build-and-run`

## Adding and rolling
1. Use the `.showtemplate` and copy the template arguments
2. Fill out your character's information
3. Add your character by using the `.addwaifu` command with your filled-out arguments
4. Use the `.rollwaifu` command to roll for the characters you added

## Vndb integration
To use vndb integration, set the type of vn characters to `vn` and ensure that the `seriesName` field matches the name of the series
as seen on vndb
 
