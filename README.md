# docker-game

Docker image of DOS game running on js-dos

run the following to build

```bash
GAME_TAG=scorch
GAME_URL=https://archive.org/download/msdos_festival_SCORCH15/SCORCH15.ZIP
GAME_ARGS=\"SCORCH.EXE\"
docker build \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t docker-$GAME_TAG .
```

once you have built the image, run with

`docker run -d -p 8000:8000 docker-$GAME_TAG`

## Examples

```bash
GAME_TAG=scorch
GAME_URL=https://archive.org/download/msdos_festival_SCORCH15/SCORCH15.ZIP
GAME_ARGS=\"SCORCH.EXE\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```

```bash
GAME_TAG=secretagent
GAME_URL=https://archive.org/download/SecretAgent_945/AGENT.ZIP
GAME_ARGS=\"SAM1.EXE\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```

```bash
GAME_TAG=cosmo
GAME_URL=https://archive.org/download/CosmosCosmicAdventure/CosmosCosmicAdventure-ForbiddenPlanet-Adventure1Of3V1.20sw1992apogeeSoftwareLtd.action.zip
GAME_ARGS=\"COSMO1.EXE\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```

```bash
GAME_TAG=doom
GAME_URL=https://archive.org/download/DoomsharewareEpisode/doom.ZIP
GAME_ARGS=\"DOOM.EXE\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```

```bash
GAME_TAG=doom
GAME_URL=https://image.dosgamesarchive.com/games/keen-shr.zip
GAME_ARGS=\"KEEN.BAT\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```

```bash
GAME_TAG=simcity
GAME_URL=https://archive.org/download/msdos_SimCity_Classic_1994/SimCity_Classic_1994.zip
GAME_ARGS=\"SIMCITY.EXE\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```

```bash
GAME_TAG=colossalcave
GAME_URL=https://archive.org/download/ColossalCave1984WillieCrowtherJerryD.PohlAdventureInteractiveFiction/ColossalCave.zip
GAME_ARGS=\"COLOSSAL.EXE\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```

```bash
GAME_TAG=civilization
GAME_URL=https://archive.org/download/msdos_sid_meier_civilization/Civilizations.zip
GAME_ARGS=\"CIV.BAT\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```

```bash
GAME_TAG=spacequest4
GAME_URL=https://archive.org/download/msdos_Space_Quest_IV_-_Roger_Wilco_and_the_Time_Rippers_1991/Space_Quest_IV_-_Roger_Wilco_and_the_Time_Rippers_1991.zip
GAME_ARGS=\"SQ4.BAT\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```

```bash
GAME_TAG=kingsquest5
GAME_URL=https://archive.org/download/msdos_Kings_Quest_V_-_Absence_Makes_the_Heart_Go_Yonder_1990/Kings_Quest_V_-_Absence_Makes_the_Heart_Go_Yonder_1990.zip
GAME_ARGS=\"SIERRA.EXE\"
docker build \
  --no-cache \
  --build-arg GAME_URL=$GAME_URL \
  --build-arg GAME_ARGS=$GAME_ARGS \
  -t magicalyak/docker-games:$GAME_TAG .
```
