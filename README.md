# Ay-eye Minigames

A **standalone, framework-agnostic** pack of 70 cinematic skill-check minigames
for FiveM, with one clean export API. No ESX, QBCore, QBox, or ox_lib required.
Drop it in, call it from any script, get a `true`/`false` back.

### [Live Preview](https://eye-minigames.vercel.app/) 
#### [Join Our Discord Community for more releases & Updates!](https://discord.com/invite/BN34qUeKwY) 

---

## The games (70 total)

### Essentials (8 — the everyday workhorses, fit any script)

| id | name | mechanic | good for |
|----|------|----------|----------|
| `skillcheck` | Skill Check | sweep a marker into the zone (multi-round) | the universal one — any job/crime action |
| `lockpick` | Lockpick | rotate pick to each hidden sweet spot | doors, vehicles, safes, lockers |
| `keypad` | Keypad | deduce a hidden PIN from ●/○ feedback | doors, safes, alarms, terminals |
| `quicktime` | Quicktime | press a key sequence before each timer | struggles, repairs, chases, QTEs |
| `mash` | Mash | spam SPACE to fill a draining bar | break free, CPR, prying, pushing |
| `reaction` | Reaction | wait for green, tap fast (no early starts) | reflex gates, quickdraw, sobriety |
| `stacker` | Stacker | drop sliding blocks to stack a tower | loading, assembling, packing |
| `targets` | Targets | click pop-up targets, dodge red decoys | aim gates, fast interactions |

### Core (10)

| id | name | mechanic | good for |
|----|------|----------|----------|
| `livewire` | Live Wire | drag-match colored wires | electrician, panel hacks, fuse boxes |
| `flatline` | Flatline | defib rhythm timing (SPACE in green zone) | EMS, revives |
| `deadcalm` | Dead Calm | sniper breath control (hold SPACE, click) | hits, hunting, ranges |
| `ghostsignal` | Ghost Signal | tune frequency + phase to a hidden wave | surveillance, jamming, radios |
| `steadydose` | Steady Dose | keep needle in a moving band (mouse) | medic, drugs, lab work |
| `cuttheright` | Cut The Right One | read clue, cut the correct wire | bomb defusal, traps |
| `vaultspin` | Vault Spin | analog combination dial (drag) | safes, vaults |
| `bluff` | Bluff | read NPC tells, call or fold | interrogation, deals, poker |
| `decrypt` | Decrypt | type streaming code tokens | hacking, terminals |
| `gaslight` | Gaslight | flash-memory recall | witness, recon, observation |

### Advanced (8 — inspired by well-known game mechanics)

| id | name | mechanic | inspired by | good for |
|----|------|----------|-------------|----------|
| `overflow` | Overflow | rotate pipe tiles to connect source→drain | Pipe Dream / BioShock | plumbing, gas, fluid systems |
| `breachmatrix` | Breach Matrix | hex sequence injection, row/col picks | Cyberpunk Breach Protocol | advanced hacking, terminals |
| `daemonrun` | Daemon Run | maze data-grab while dodging a trace | Pac-Man-style hacks | data heists, ICE evasion |
| `pulse` | Pulse | 4-lane rhythm note hitting (D F J K) | Guitar Hero / rhythm | DJ, music, timing-heavy jobs |
| `hottrace` | Hot Trace | drag a probe through a corridor, no walls | Operation / wire-loop | surgery, delicate wiring, defusal |
| `cascade` | Cascade | escalating Simon-says pattern memory | Simon / Bop It | keypads, memory locks |
| `lightsout` | Lights Out | flip cells (and neighbours) until every light is off | Lights Out | logic locks, fuse boxes, terminals |
| `slidepuzzle` | Slide Puzzle | slide the scrambled tiles back into 1..N order | 15-puzzle | locks, repairs, decryption, terminals |

### AAA-Inspired (8 — premium signature mechanics)

| id | name | mechanic | inspired by | good for |
|----|------|----------|-------------|----------|
| `resonance` | Resonance | tune sine sliders so your wave matches a target (one "inverts voltage") | Marvel's Spider-Man circuit puzzles | calibration, lab hacks, repairs |
| `intrusion` | Intrusion | hop the signal through a node network, dodge monitored (red) nodes | Watch Dogs camera/ctOS hopping | advanced hacking, CCTV, infiltration |
| `override` | Override | lock spinning concentric rings at the top notch before corruption fills | Horizon Zero Dawn override | machine/drone takeover, control hacks |
| `animus` | Animus | rotate concentric rings to align all key segments to one spoke | Assassin's Creed animus/glyph | ancient locks, sync points, relics |
| `eaglevision` | Eagle Vision | memorize a target signature, then click every match among decoys | AC eagle vision / spider-sense | recon, target ID, surveillance |
| `parry` | Deflect | parry each incoming strike with the right arrow inside the timing ring | Sekiro / soulslike | melee duels, struggles, defence |
| `constellation` | Stargazing | connect the numbered stars in order to trace the constellation | AC / Ghost of Tsushima | rituals, recon, observation, lore |
| `archery` | Longshot | drag from the bow toward the target & arc the shot onto it (trajectory preview) | Horizon / Tomb Raider | hunting, archery, ranged skill checks |

### Jobs (14 — job-specific)

| id | name | mechanic | good for |
|----|------|----------|----------|
| `fishing` | Fishing | wait for the bite, then keep the fish in the zone while reeling | fishing job |
| `mining` | Mining | strike the glowing crack before it fades, dodge misses | mining, quarry |
| `cooking` | Cooking | multi-step timing — hit each stage in the green | cooking, crafting |
| `welding` | Welding | drag the torch along a seam at steady speed without overheating | mechanic, repairs, fabrication |
| `harvest` | Harvest | rhythm — cut each crop as it crosses the line | farming, weed/coca trim |
| `drilling` | Drilling | hold to drill, keep pressure in the green without overheating | drilling, breaching, oil |
| `locksmith` | Locksmith | raise each pin to its shear line and set it | doors, locks, repo |
| `hotwire` | Hotwire | connect the wires, then time the ignition spark | car theft, boosting |
| `crafting` | Crafting | memorize the recipe, then add ingredients in order | crafting, chemistry, cooking |
| `lugnuts` | Lug Nuts | torque each wheel nut in star order — stop the needle in the green | mechanic, tyre shop, repairs |
| `paintspray` | Paint Booth | spray the panel to even coverage without over-soaking (drips) | bodyshop, resprays, detailing |
| `crane` | Cargo Crane | lead the pendulum swing and drop crates onto the truck | docks, warehouse, loading |
| `forge` | Blacksmith | strike the metal while it glows in the green heat window | smithing, weapon/tool crafting, metalwork |
| `diving` | Salvage Dive | grab the loot, surface to breathe before air runs out | diving, salvage, smuggling, search & rescue |

### Mechanic (4 — sorting & moving things around)

| id | name | mechanic | good for |
|----|------|----------|----------|
| `partsort` | Parts Sort | send each part to its matching bin (1 / 2 / 3) | mechanic, warehouse, parts shop, recycling |
| `toolbox` | Tool Board | drag each tool onto its matching shadow outline | mechanic, garage, organizing, prep |
| `packing` | Crate Packing | drag every part into the crate so they all fit (Tetris-style) | warehouse, shipping, loadouts, storage |
| `beltsort` | Quality Control | pull the cracked parts off the conveyor, let good ones pass | factory, assembly line, inspection, recycling |

### Crime (6 — illegal jobs)

| id | name | mechanic | good for |
|----|------|----------|----------|
| `tripwire` | Tripwire | weave past sweeping lasers to the exit — one touch = caught | infiltration, heists, security rooms |
| `pickpocket` | Pickpocket | hold to lift, release before the mark glances at you | theft, lifting, stealth |
| `getaway` | Getaway | swap lanes to dodge oncoming traffic and survive the run | chases, getaway driver, street racing |
| `cashcount` | Count The Take | click bills to hit the exact amount (undo to fix overcounts) | robbery loot, drug deals, laundering |
| `counterfeit` | Counterfeit | drag the plate onto the guides and hold it aligned to print | fake bills, forged documents |
| `chopshop` | Chop Shop | hold on each car part to unbolt it before the heat maxes out | stolen car stripping, parts fencing |

### Medical & Rescue (3)

| id | name | mechanic | good for |
|----|------|----------|----------|
| `suture` | Suture | click each stitch as its ring shrinks into the green | EMS, surgery, field medic |
| `bonepin` | Bone Set | drag fractured fragments into their matching slots | orthopedics, surgery, first aid |
| `vitals` | Vitals | keep three drifting gauges in the green — tap 1 / 2 / 3 | EMS monitoring, ICU, anesthesia |

### Police & Forensics (2)

| id | name | mechanic | good for |
|----|------|----------|----------|
| `fingerprint` | Fingerprint | match the scanned print — click the identically-oriented one | police, forensics, evidence, access ID |
| `breathalyzer` | Breathalyzer | hold to blow, keep airflow in the green to log a clean reading | DUI stops, sobriety, medical |

### Drugs & Chemistry (2)

| id | name | mechanic | good for |
|----|------|----------|----------|
| `titration` | Titration | pour reagent and stop exactly in the narrow target band | drug labs, chemistry, lab work, brewing |
| `pillpress` | Pill Press | time each press stroke to stamp a clean pill | drug production, pharma, manufacturing |

### Heist (5)

| id | name | mechanic | good for |
|----|------|----------|----------|
| `thermite` | Thermite | memorize the lit cells, then burn the same ones back | vault breaches, doors, fleeca/pacific |
| `lasergrid` | Laser Grid | guide the cursor to the exit without touching a sweeping laser | infiltration, vaults, museums |
| `vaultdrill` | Vault Drill | stop each drill point in the green core | safes, vaults, ATMs |
| `jammer` | Signal Jammer | jam each alarm channel as its bar peaks | alarms, cameras, security |
| `dataheist` | Data Heist | catch the clean data packets, dodge the corrupt red ones | hacking, data steals, USB grabs |

---

## Install

1. Drop the `eye_minigames` folder into your `resources`.
2. Add to `server.cfg`:
   ```
   ensure eye_minigames
   ```
3. (Optional) rename the folder — just keep it consistent with the
   `ensure` line. The export name follows the folder name.

No database, no dependencies.

---

## Usage

### Blocking (recommended — runs inside a thread)

```lua
CreateThread(function()
    local ok = exports.eye_minigames:Play('vaultspin', {
        difficulty = 3,                 -- 1 (easy) .. 5 (brutal)
        tumblers   = 4                  -- per-game option (see table below)
    })

    if ok then
        print('cracked the safe!')
        -- TriggerServerEvent('myheist:vaultOpen')
    else
        print('failed')
    end
end)
```

### Non-blocking (callback)

```lua
exports.eye_minigames:Start('flatline', { difficulty = 4 }, function(ok)
    if ok then
        -- revive logic
    end
end)
```

---

## Chain mode (multi-game sequences)

Run several minigames back-to-back — perfect for heists and multi-stage
jobs. Blocking; returns `success, completed, total`.

```lua
CreateThread(function()
    -- simple: list of ids, shared difficulty
    local ok, done, total = exports.eye_minigames:PlayChain(
        { 'lockpick', 'breachmatrix', 'override' },
        { difficulty = 3 }
    )
    if ok then
        print('full chain cleared!')
    else
        print(('failed at stage %d/%d'):format(done + 1, total))
    end
end)
```

Per-stage control (different game settings each step):

```lua
exports.eye_minigames:PlayChain({
    { game = 'lockpick',     difficulty = 2 },
    { game = 'breachmatrix', difficulty = 4 },
    { game = 'override',     difficulty = 5, allowCancel = false }
})
```

Chain options: `difficulty`, `allowCancel`, `stopOnFail`
(default `true` — stop the moment a stage is failed).

---

## Options

Every call takes an options table. All fields optional.

| field | type | default | notes |
|-------|------|---------|-------|
| `difficulty` | number 1–5 | per-game (config.lua) | scales speed/size/timer |
| `allowCancel` | bool | `Config.AllowCancelByDefault` | ESC to bail |

Per-game extras:

| game | extra option | default |
|------|--------------|---------|
| `skillcheck` | `rounds` | 2 + diff/1.5 |
| `flatline` | `rounds` (shocks needed) | 3 |
| `deadcalm` | `shots` | 3 |
| `vaultspin` | `tumblers` | 2 + diff/2 |
| `bluff` | `hands` | 3 |

All advanced games are driven purely by `difficulty` (1–5) — no extra
options needed.

---

## Test in-game

Test commands are on by default (`Config.EnableTestCommands`). Turn the
flag off in `config.lua` for production.

```
/mg <id> [difficulty]   play one game, e.g. /mg lockpick 4
/mglist                 list every game id by category
/mgrandom [difficulty]  play a random game
/mgall [difficulty]     play every game back-to-back (QA sweep)
```

Results print to console and chat. The commands have chat autocomplete
suggestions.

---

## Sound

Synthesized sound effects (Web Audio — no audio files, zero extra deps).
Clicks, ticks, success/fail stings, and per-game cues are built in.

Global toggles in `config.lua`:

```
Config.Sound  = true    -- master on/off
Config.Volume = 0.5     -- 0.0 - 1.0
```

Override per call:

```
exports.eye_minigames:Play('lockpick', { difficulty = 3, sound = false })
exports.eye_minigames:Play('mining',   { difficulty = 2, volume = 0.8 })
```

---

## Notes

- Pure client-side skill checks. `server/main.lua` is a stub for your own
  anti-abuse hooks (rate-limiting etc.).
- Built on canvas + vanilla JS NUI. Zero external runtime deps.
- One game runs at a time; concurrent calls return `false` immediately.
