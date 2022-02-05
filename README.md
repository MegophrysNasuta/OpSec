# OpSec

## Step 1: Install

Install the OpSec.mpackage in this repository to get access to the main
aliases and triggers.

## Step 2: Check Room Security

Run `opsec` in any room to get a report about the totem (if any), whether
or not a flamed monolith is present, and any wormholes (if you have that
skill). You will also get a warning if the totem is not empowered.

## Step 3: (Optional) Get Security Walk from Nasuta

Reach out to me (Nasuta) in game to see if I have a walk script for your
city. These are currently available for Targossas, Hashan, and Mhaldor at
the time of this writing. Running this additional alias will autowalk your
city collecting these reports. You can display the collection (it will 
automatically be shown at the end) with `opsec display`.

This script is RP-friendly and poses and emotes to show you checking the
totems, restoring your previous pose (if any) at the end.

## Step 4: (Optional) Configure wormhole checks

If you do not have a wormholes artefact, you can go to the top of the
`Check Room Security` alias and set `opsec.checkWormholesAlways = true` to
also check those in each room.

## Step 5: (Optional) Log to city

Once you've run the security walk a few times, and you're comfortable it's
generating correct data, you can `opsec logreport` to automatically write
this to your city log. Do test this before you spam the logs!
