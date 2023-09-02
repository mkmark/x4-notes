# X4 notes

<!-- toc -->

- [objectives](#objectives)
  * [guideline](#guideline)
  * [outline](#outline)
- [general stratagy](#general-stratagy)
  * [game basic flow](#game-basic-flow)
  * [bailing](#bailing)
  * [boarding](#boarding)
  * [faction reputation fix](#faction-reputation-fix)
    + [reputation fix for below -10](#reputation-fix-for-below--10)
    + [reputation fix for >= -9](#reputation-fix-for---9)
      - [manual way](#manual-way)
      - [automatic way](#automatic-way)
  * [drop collection](#drop-collection)
  * [gate defense](#gate-defense)
  * [shipyard block](#shipyard-block)
- [full loop factory](#full-loop-factory)
  * [workforce](#workforce)
  * [xml editing](#xml-editing)
- [terraforming](#terraforming)
  * [fund start-up](#fund-start-up)
- [plots](#plots)
  * [Hatikva's plot](#hatikvas-plot)
  * [CoH plot](#coh-plot)
  * [ToA plot](#toa-plot)
  * [other plots](#other-plots)
- [best equipments for specific purposes](#best-equipments-for-specific-purposes)
- [best ships for specific jobs](#best-ships-for-specific-jobs)
  * [drop collector](#drop-collector)
  * [reputation trader](#reputation-trader)
  * [miner](#miner)
  * [misson/personal ship](#missonpersonal-ship)
  * [scout](#scout)
  * [gate defender](#gate-defender)
  * [personal battle ship](#personal-battle-ship)
  * [boarder](#boarder)
  * [builder](#builder)
  * [sightseeing](#sightseeing)
  * [XL ship M dock additional M turrets](#xl-ship-m-dock-additional-m-turrets)
- [modification](#modification)
  * [sources](#sources)
  * [numerical target](#numerical-target)
- [resources](#resources)
  * [station plans](#station-plans)

<!-- tocstop -->

## objectives

### guideline

from the most important

1. vanilla, no cheating, no modding, no editing
1. make as few irreversible decisions as possible
1. make as many available options as possible
1. as much automatic as possible
1. keep the efficiency as high as possible to leviate cpu stress

### outline

- ability to produce every ship, ware, station module
  - with the exception of useless ones (like Prometheus because I won't use these ships in any situations anyway)
  - reputaion for factions
    - reputation fix for below -10
      - station criminal traffic shooting
    - reputation fix for above -10
      - fast ship trading
    - yiki reputation by push the plot to the 
- as many inventory items as available
  - xenon gate drop collection
    - xenon gate defense
    - xenon gate drop collector

## general stratagy

### game basic flow

1. do Hatikva, CoH plots until Yaki reputation level 0
1. set up drop collectors (hours into game)
1. set up HQ research (hours into game)
1. set up reputation traders (hours into game)
1. fly-by board Asgards and set up gate defense (several hours into game)
1. start setting up miners (several hours into game)
1. start setting up HQ production modules (a day into game)
1. set up shipyards blocking ships (a day into game)
1. seta, finally (feel one can count this as the end game, about 2 days into the game)
1. do terraforming

### bailing

- hard limit: if hull<75%, shield<25%, then bail check every 30 seconds
- your own max hull points matter, the bailing chance *= (target_max_hull/your_max_hull)
- check point can be revealed by communicating with the pilot, if they respond then the next damage/surrender command will cause bail check
- Yaki Kurokami and Moreya are great bailing targets early game, just attack from the subordinates (usually casaded so make sure you are not attacking any leader) and they will not fight back

see also

- [Bailing: Capturing S and M sized ships : X4Foundations](https://www.reddit.com/r/X4Foundations/comments/a93lhf/bailing_capturing_s_and_m_sized_ships/)
- [Surrender ! command : X4Foundations]https://www.reddit.com/r/X4Foundations/comments/tuep96/surrender_command/

### boarding

- prepare a ship with large crew, for example Shuyaku Vanguard, disarm all turrents, remove all cargo drones.
- buy marines from VIG shipyard, note thet crew can be transferred over distance so you don't the boarding ship be the actual buyer
  - transfer all the marines with 1.3 star and sell the rest, repeat until you have a full ship of 1.3 star marines
- good boarding targets include TER intervention corps Asgard and Tokyo, petrol Asgard as the Moon gate (to Venus)
- Treval mode fly by target right beneath its belly, pause, lauch marines with both conditions set to 'very strong', unpause. If you bump into the target, pause and deactivate fly assistance then unpause
- remove the boarding command from the ship, fly to safe area

see also

- [Fast money guide by boarding terran capital ships : X4Foundations](https://www.reddit.com/r/X4Foundations/comments/s08c4t/fast_money_guide_by_boarding_terran_capital_ships/)

### faction reputation fix

A lot of equipment are locked behind the repuatation, so one need to unlock these reputation fast.

#### reputation fix for below -10

Find a station, or better several stations close to each other, you need to wait until a criminal traffic pop up then shoot it. The criminal vesssel is spawed on interval, and stations nearby will spawn on seperate timers, but you need to get there to 'discover' the target.

#### reputation fix for >= -9

##### manual way

If you want to raise reputation fast, 100 energy cells sold one by one will raise the reputation from 0-11 in several minutes.

##### automatic way

Get a fast ship, set on repeat orders to sell wares one at a time, e.g. buy 10 energy cells and sell one at a time. Though, buy one sell one seems efficient enough if the distance between stations is not far. Can configure multiple selling target station to avoid failling to sell. This will level from 0 to 30 in about 3 days.

### drop collection

This is the best investiment one can made in the game, though quite risky if the ship assigned is not fast/tanky enough.

It will give you:

- one of your main income sources, enen in late game
  - programmable field array to sell for quite a fortune
  - spacefly eggs for crafting spacefly cavier for quite a fortune
- basic modifications
- modification components (consummables)
- seta components
- materials needed for unlocking black markets
- ...

It requires you 

- set up a S/M ship on repeat orders on 'collect drops' near a Xenon gate
  - add a command to dock at the nearest station / your asgard if you have one defending this gate to maximize efficiency / ensure safety
  - do not let the pilot use judgement, override this so the pilot always flee under attack
- guarantee Xenon production (do not let NPC factions destroy Xenon logistics)

The best sector for this is Hatikva's Choice, but almost every Xenon gate will do just fine.

### gate defense

So that Xenon does not destroy core stations like Equipment Dock in Family Tkr.

It will give you:

- safer working environment for your drop collector
- guarantee a place to by/repair/update your ships before you have your own facility

It requires you

- have an Asgard stationed there
- or at least, when it's an emergency, any personal piloted M ship to disable the invader's engine and turret so that local reinforcements can finish it

An Asgard may not be enough. You may need to teleport there to save it.

A defense station may be the best defender, but is rather inflexible (say if you want to remove the block and let Xenon pour in). I may do this in future.

### shipyard block

If not blcoked, NPC faction will produce capital ships threatening Xenon or their own neighbours. Buy/dock ships (usuablly 2 L 1 XL) in their fabrication bay to block their production.

- pause game right at ship construction 100% finished
- issue a dock and wait command and remove the undocking command
- fire/remove the pilot

Occationally fired/removed pilot may still managed to undock the ship before fired/removed. You will need to redock the ship (best in person) to the dock. Do not request docking permission, just fly into the intended fabrication bay and the correct docking permission will be auto granted.

A ship with no pilot (excluding yourself) will not be removed in any way, thus a reliable block on the shipyard, much better than production module hacking or other methods.

FAF cannot build their pirate ships in this way, which is a highly preferable side effect, and saves one's trouble to do Split plots.

But SCA ships can still be there, because they are spawned.

## full loop factory

It will give you:

- every ware you need at no cost
- decent credits
- terraforming capability

It requires you

- use your own builder
  - for 30 building drones so construcntion is proceeded in 100% efficiency
  - for 219 crew super fast training
- have your own miners
  - for saving the cost and make the resources reliable
- build ships and sell them manually to shipyards for controlled results / best credits
  - If you let NPC buy ships directly, they will actully use the ships, causing potential regional problems. And they pay 20%-30% only.
  - If you sell the ships to a shipyard, ships will fly there and be recycled into materials, and you get full (selling price) credits

I build all the module to my HQ.

The reason to set up only one factory, at the price of slow construction, is to avoid any kind of logistic nightmare. The ships and factory numbers will be reduced to minimum for the same amout of ware produced, as obejctives require. Other than that, the entire sturucture can be teleported anywhere.

The only potential loss of such a strategy is inability to utilize the mineral resources of other then local areas, and potential GPU performance issue when at HQ.

To avoid troublesome planning, I put all my modules (except docking modules) at position 0,0,0 via xml editing. This yields very clean plan (both in game and in xml), and almost all modules are hidden in the HQ astroid. I can not measure the exact performance issue caused by z-fighting, but 200 modules there seems not a problem for GTX2080.

The plan is available at `constructionplan/7.xml`.

The docking piers are put in such a way to allow as many to function as possible. (6 faces of the cube considered)

Then, use terran docking piers and fabrication modules for aesthetic reasons.

Build in certain sequence to optimize building time production, mostly in a stage by stage manner.

see also

- [Build drones for wharf. How many? - egosoft.com](https://forum.egosoft.com/viewtopic.php?t=428052)

### workforce

Workforce can be seen as providing 20-50% of the output (at all production stages!) with ice, which is easy to mine and quite abundant.

The down side is that, unlike silicon and ore which will not be consumed when the module is not producing, ice will be consumed to support workfoce continuously. It is fair though, as the employees cannot be fired simply because the factory is not working. It is not fair that, the workforce will not shift themselves to those actual producing modules.

Use Argon workforce for long term benefits.

see also

- [Profitable Racism: The Most Profitable Race to Crew Your Station : X4Foundations](https://www.reddit.com/r/X4Foundations/comments/w3j32n/profitable_racism_the_most_profitable_race_to/)

### xml editing

- entry index does not matter, the sequence matters
  - import then export the plan will generate correct indices
- 0 value property can be omitted, and will be automatically ommited when exporting from the game
- a basic cross connector is a 400m length cube centered at (200,200,200), most modules follow the 400m grid
- snap in game does not guarantee precise alignment, you will notice small error like 0.0052 in the xml
- exact marco with exact the same offset will be preserved, otherwise will be teared down and rebuilt

## terraforming

The actual usage of terraforming is to cause a need for production... So you can still play the game if you are not war with someone. but there are benefits too, the most important ones being the ability to train pilots (although troublesome), and ability to do start-up funding.

In my current gameplay I do not have much sources of credit income, so start-up funding might just be the way for me to earn my blueprints.

see also

- [Terraforming - Notes on/How I completed each project - egosoft.com](https://forum.egosoft.com/viewtopic.php?f=182&t=441523&p=5075536#p5075536)

### fund start-up

High school mathematics.

The expectation output (of unit investiment) is

$$
E(X) = 0.1 \times 15 = 1.5 > 1
$$

Seems fine, but there is a trick. The investiment amount is not entirely controllable by the player. It is in fact, fixed to 10% of the player cash amount when the mission is provided. This mechanic actually lowers one's ability to profit and adds some problem, because you will now have to own 10 times more to be able to invest the same amount.

Under such terms, there is a 35% chance that a player fails 10 times in a streak (I'm currently on 20 and decided to look into the problem) and the final pay does not cover their loss.

However, given a proper strategy, that one always invests an calculated amount so as to always win back the summ of former losses, one can always make money in the end.

To achieve the above stratagy, between two investiment cycles, the player need to make their total cash 1+all_previous_loss/15 the next time.

<details>

$$
a_1 = 1, p = \cfrac{0.1}{15}, s_n = \sum_{i=1}^{n}{a_i}
$$

$$
a_n = 1 + p s_{n-1}
$$

$$
\therefore s_n - s_{n-1} = 1 + p s_{n-1}
$$

$$
\therefore s_n  = 1 + (p+1)s_{n-1}
$$

$$
\therefore s_n + \cfrac{1}{p} = (p+1)(s_{n-1}+\cfrac{1}{p})
$$

$$
\therefore s_n = (1+\cfrac{1}{p})(1+p)^{n-1} - \cfrac{1}{p}
$$

$$
\therefore a_n = (1+\cfrac{1}{p})(1+p)^{n-1} - (1+\cfrac{1}{p})(1+p)^{n-2}, n>=2
$$

</details>

$$
\therefore a_n = 151 \times ((\cfrac{151}{150})^{n-1} - (\cfrac{151}{150})^{n-2}), n>=2
$$

To give a sense, here is $a_1$ to $a_{40}$.

| no | total    | no | total    | no | total    | no | total    |
|----|----------|----|----------|----|----------|----|----------|
| 1  | 1        | 11 | 1.068703 | 21 | 1.142125 | 31 | 1.220592 |
| 2  | 1.006667 | 12 | 1.075827 | 22 | 1.14974  | 32 | 1.22873  |
| 3  | 1.013378 | 13 | 1.083    | 23 | 1.157404 | 33 | 1.236921 |
| 4  | 1.020134 | 14 | 1.09022  | 24 | 1.16512  | 34 | 1.245167 |
| 5  | 1.026935 | 15 | 1.097488 | 25 | 1.172888 | 35 | 1.253468 |
| 6  | 1.033781 | 16 | 1.104804 | 26 | 1.180707 | 36 | 1.261825 |
| 7  | 1.040673 | 17 | 1.11217  | 27 | 1.188579 | 37 | 1.270237 |
| 8  | 1.04761  | 18 | 1.119584 | 28 | 1.196502 | 38 | 1.278705 |
| 9  | 1.054595 | 19 | 1.127048 | 29 | 1.204479 | 39 | 1.28723  |
| 10 | 1.061625 | 20 | 1.134562 | 30 | 1.212509 | 40 | 1.295812 |

So, a proper investiment plan would be to put only a fraction of your total cash as your initial flown cash, then act according to the strategy. How much? Depends on how much risk you want to take. To prepare a streak of 10, 20, 30, 40 failed investiments, with the probability of 0.3487, 0.1216 (me right here), 0.0424, 0.0148 accordingly, the additional 1.031, 2.132, 3.309, 4.567 unit of cash should be frozen somewhere. Note this does not take your passive income into consideration.

Say you want a 87.85% secure investment (20 fail chances), you need to put 1/(1+2.132) total cash in the account, then before getting next investment offer, refill the account to next status.

Once you make a successful investiment, the entire strategy is reset and you'll snowball exponentially.

This is meant to be an interesting mechainic, as credits have almost no usage in late game, for example when you are terraforming (unless you actually rushed here for this start-up funding like me... good luck).

On the other hand, save spam should work, but in a special way. According to some speculation and my own observation, the consecutive results may be only updated after a success mission. This seems to be some deliberate anti save-spam mechanic, at least it makes sure you cannot have a success every time. So save spam (before getting the offer) but use very little account money, and revert to the latest save when the result is a success and put all you have in your own accont.

I succeeded on the 22nd trial.

see also

- [Fund Start-up Question :: X4: Foundations General Discussions](https://steamcommunity.com/app/392160/discussions/0/3056241311833145484/)

## plots

The plots in X series are always optional. I do not need, or want to experience the trashy scripts and buggy plots by any means, so I only opt to do the most rewarding plots with no significant consequences.

see also

- [5.0 ToA Plots Flowchart : X4Foundations](https://www.reddit.com/r/X4Foundations/comments/tsy4u2/50_toa_plots_flowchart/)

### Hatikva's plot

No decisions need to be made here, and this plot opens up options for other plots.

see also

- [[Guide] Hatikvah Plot Walkthrough : X4Foundations](https://www.reddit.com/r/X4Foundations/comments/rxa1v6/guide_hatikvah_plot_walkthrough/)

### CoH plot

I do this plot to unlock Yaki reputation.

Push until you can dock on the Yaki pirate station, so that you can raise the reputation with trading and consequently unlock their blueprints, stop right here to preserve the ship with unique clock

- one irreversible decision and one easy-to-miss opportunity
  - giving Litigious Rodent to Bosa results in the Moreya to have the cloak with no pilot available on board (until finish the plot which I intend not)
  - giving Litigious Rodent to TSS reuslts in a Katana to have the cloak, and you can assign a pilot before undocking. The assigned pilot can not excute any command though. They will have blue identity like allied pilots, but you can communicate them correctly. You can reassign the pilot elsewhere later, but none can be assigned here from now on. If you exchange pilots with other ships, the one to be exchanged to the Katana will vanish.

The choice boils down to, whether to put the cloak on a Moreya or a Katana. I have blueprints of both, so nothing special here. Moreya is the fastest S ship that can install a TER engine, and Katana is the fastest M ship that can install a TER engine. Both have distinguished ship paint, and the Katana gets a slightly better one, but this is no important reason. It's better to think in a perspective, that who gets more benefit from such a cloak.

In real life, high speed scout does not need a cloak, the speed is its best protection, so is Moreya.

The Katana, on the other hand, can achieve things a Moreya cannot do, for example, survive friendly fire when accidently activating the cloak near allies, and can kill almost any ship with less effort than a Moreya (How do you even kill a battleship with a Moreya?).

Katana it is.

see also

[Spoilers: Compilation of New Plot Rewards - egosoft.com](https://forum.egosoft.com/viewtopic.php?f=182&t=434917)

[Yaki Plot Combinations - egosoft.com](https://forum.egosoft.com/viewtopic.php?t=451776)

### ToA plot

I do this plot to get Astrid.

The only decison to be made here is whether to side with the twins or against them. The latter option gives the blueprint, which is not available otherwise.

I need to finish the plot to get the Astrid, speaking of which is so ugly and not quite useful. A Moreya/Katana can do a better job moving everywhere and be used as a personal ship when required, in comparision the manuvability of Astrid is too aweful to be used personaly. The best use might be to quickly fly and dock on a unteleportable station so I can teleport there fast, even then it's a M ship thus too far away from the telepotation room.

see also

- [*SPOILERS* TOA Plot Questions *SPOILERS* :: X4: Foundations Spoiler Discussions](https://steamcommunity.com/app/392160/discussions/2/3176733459037505428/)

### other plots

I put all other plots, together with the remaining part of the CoH plot on hold. These plots tend to have irreversible decisions with little benefits to my goals.

For example, Paranid plot will unlock BUC reputation which I tend to avoid so I can keep harvesting exceptional chasis mod at no loss.

## best equipments for specific purposes

- shield
  - TER
    - fast regen rate with almost the best capacity
    - exclusive MK3 M shield
  - TEL
    - best capacity with worst regen rate
- engine
  - TER
    - exclusively best treval boost, much better than any other engines
  - SPL
    - exclusively best combat MK4 for best crusing speed
- turrent
  - PAR L plasma: best IS/OOS anti capital
  - ARG M flak: best IS anti fighter, good OOS performance
- weapon
  - TER M meson stream MK2: best OOS, very hard to hit fighters in player's control, barely acceptable IS
  - TER M proton barage: second best for TER ship OOS, accecptable IS

see also

- [X4: Foundations Ultimate Weapons Guide](https://www.riotbits.com/x4-foundations-ultimate-weapons-guide-52654/)
- [Gearing ships for Out of Sector (OOS) Combat setup (as of 2020)? : X4Foundations](https://www.reddit.com/r/X4Foundations/comments/kjwat5/gearing_ships_for_out_of_sector_oos_combat_setup/)

## best ships for specific jobs

### drop collector

Large ships collect drops with very slow drones, which is not an option. No ship can promise survivability near a Xenon gate, especially a S/M one. It requires to be fast (cruising speed) enough to be able to flee, and tanky enough before it managed to get away.

- Katana
  - exceptional mod: Nanotube
  - engine
    - SPL combat engine MK4
      - basic mod: Nudger
  - shield
    - TER M shield MK3
      - exceptional mod: Targe
  - weapon
    - TER meson stream MK2
      - basic mod: Slasher
  - turret
    - ARG flak MK1
      - basic mod: Slasher
  - high level pilot
  - high level crew

Make no mistake here, any ship, even the starting Elite Vanguard can do the job, just very likely to die fast. A non-modded Katana with SPL MK3 is acceptable in early game.

### reputation trader

**speed**

- Moreya
  - engine
    - TER combat
  - shield
    - TER
- Moreya
  - exceptional mod: Tenacity, for RIP
  - engine
    - TER combat
  - shield
    - TER
- Pegeasus, if you cannot get (enough) Moreyas yet
- Katana, proper shields for traveling to Yaki in deep Xenon territory
  - exceptional mod: Shroud, analogue to reallife stealth
  - engine
    - TER combat
    - basic mod: Reaver

### miner

**efficiency (cargo, speed)**

- Crane Sentinel
  - exceptional mod: Nanotube
  - engine
    - TER all-round
      - basic mod: Reaver
  - shield
    - TER
      - basic mod: Buckler
  - turret
    - TEL/any mining
      - basic mod: Digger
    - ARG flak
      - basic mod: Slasher
  - 4-5 star pilot
  - 4-5 star crew

A typical Crane Sentinel will mine and sell a full shipload in about 20-25 minutes, which is highly efficient. 15 mineral + 2 gas such miners can support my 480 module HQ with redundancy.

The logic of choosing cargo over speed, is that despite the mining process is mostly bottlenecked by the delivery process, the delivery process is not completely controlled by top travel speed. The rotation after each jump gate, the docking process, the ware transferring process, can not be reduced by faster speed. Now almost all large miners have a similar cargo*speed, then the one with the largest cargo wins. Extra advantages include very good shields and weapons against Kha'ak.

The theory is validated by experiments.

see also

- [Initial test data from downsizing miner :: X4: Foundations General Discussions](https://steamcommunity.com/app/392160/discussions/0/3490880386666664982/)

### misson/personal ship

**travel speed, damage, shield**

- Moreya
  - exceptional mod: Nanotube
  - engine
    - TER combat
      - exceptional mod: Traction
  - shield
    - TER
      - exceptional mod: Slingshot
- Katana
- Kurokami

see also

- [What is the best equipment for the yaki corvette? : X4Foundations](https://www.reddit.com/r/X4Foundations/comments/116kbx5/what_is_the_best_equipment_for_the_yaki_corvette/)

### scout

**travel speed**

- Moreya
  - exceptional mod: Nanotube
  - engine
    - TER combat
      - baisc mod: Reaver

### gate defender

**tank, damage**

- Asgard
  - exceptional mod: Nanotube
  - engine
    - TER all-round
      - basic mod: Reaver
  - shield
    - TER
      - basic mod: Buckler
  - weapon
    - ATF XL beam
      - basic mod: Piercer, for one-shot I without creating cooling issue
    - TER L beam
    - ARG M flak

### personal battle ship

**damage, manuvability, speed, tank**

- Asgard
  - exceptional mod: Nanotube
  - engine
    - TER all-round engine
      - exceptional mod: Vikas
  - shield
    - TER shield
      - exceptional mod: Traction
  - weapon
    - ATF XL beam
      - exceptional mod: Annihilator
  - turret
    - TER L beam
      - basic mod: Slasher
      - enchanced mod: Kite/Cast
    - ARG M flak
      - basic mod: Slasher
      - enchanced mod: Kite/Cast
- Erlking
  - exceptional mod: Nanotube
  - engine
    - Erlking engine
      - exceptional mod: Vikas
  - shield
    - TER shield
      - exceptional mod: Traction
  - weapon
    - Erlking main weapon
      - exceptional mod: Annihilator
  - turret
    - Erlking turret
      - basic mod: Slasher
      - enchanced mod: Kite/Cast

### boarder

**fast, crew**

- Shuyaku Vanguard
  - exceptional mod: Nanotube
  - engine
    - TER
      - basic mod: Reaver
- Asgard
  - exceptional mod: Annihilator
    - TER engine
      - basic mod: Reaver / exceptional mod: Vikas

### builder

**fast, crew**

- Heracles Vanguard
  - exceptional mod: Nanotube
  - engine
    - TER
      - basic mod: Reaver

### sightseeing

**fast**

- Astrid
  - exceptional mod: Nanotube
  - engine
    - Astrid
      - exceptional mod: Slingshot
- Moreya/Pegasus

### XL ship M dock additional M turrets

- Jian
  - turret
    - ARG M flak
      - basic mod: Slasher
      - enchanced mod: Kite/Cast

## modification

### sources

- basic mods
  - drop collector
- advanced mods
  - Prometheus hunting
    - difficult because BUC will destroy your satellites so maybe hard to find these ships
      - as an exception, Morning Star IV lets you deploy a lot of satellites, so hunting Prometheus here is easier
      - automatic farming could be lowly efficient because most of the time these ships are cloaked
- exceptional mods
  - initial spawned Prometheus sometimes carry full exceptional mods
  - chasis
    - all BUC ships can be destroyed at no consequece to harvest exceptional chasis mods, so put some M ships on defense position with fire authorization set to ruthless, and a drop collector to farm on the same spot
  - weapon
    - guild/war missions
  - shield
    - guild/war missions
    - war missions that reward a L miner guarantee an exceptional shield mod
  - engine
    - guild/war missions, mostly often those need you to deploy resource probes
      - have shipd stationed at the deploying position to facilitate next time's operation, as the location pool is quite limited for these missions

see also

- [could use tips for where/how to farm parts for mods : X4Foundations](https://www.reddit.com/r/X4Foundations/comments/12eadge/could_use_tips_for_wherehow_to_farm_parts_for_mods/)
- [What is your favourite Mod Part "Supermarket"? - egosoft.com]https://forum.egosoft.com/viewtopic.php?f=146&t=452304


### numerical target

- chasis
  - Nanotube, every 10 rolls
    - 0.22 drag
  - Shroud
    - 0.79 visibility
- shield
  - Pavise, a lot of rolls (no consumption)
    - 0.69 shield capacity
  - Traction for S ship, a lot of rolls (no consumption)
    - 0.65 rate
    - 0.65 delay
  - Traction for M and above ship, a lot of rolls (no consumption)
    - 0.69 rate
  - Kite/Cast (these two are exact the same mod)
    - 0.19 capacity
    - 0.19 rate
- weapon
  - Slasher, every 20 rolls
    - (1+reload * 1+damage) > 2.5, e.g. 0.4 damage, 0.8 reload
  - Slasher for TER L beam, every 20 rolls
    - 0.45 damage
    - 0.67 reload (larger is useless)
  - Digger, every 20 rolls
    - 0.49 rate
  - Piercer, every 10 rolls
    - 0.19 damage
  - Annihilator, a lot of rolls
    - rare, and depends...
- engine
  - Reaver, every 20 rolls
    - 0.44 travel speed
  - Nudger, every 20 rolls
    - 0.44 forward thrust
  - Slingshot, every 1000 rolls, good that you don't need to do this very often (only for personal S/M ships)
    - 0.29 forward thrust
    - 0.49 travel thrust
  - Vikas, a lot lot of rolls (only for personal L/XL ships)
    - high rotation thrust
    - high forward thrust
    - high travel thrust

## resources

- [Quantum Anomaly](https://www.qsna.eu/x4/tips-and-tricks)
- [Roguey's X4 site](https://roguey.co.uk/x4/)
- [GitHub - Mistralys/x4-game-notes: Collection of insights on playing X4: Foundations.](https://github.com/Mistralys/x4-game-notes)
- [X4: Foundations / Kingdom End - Station Calculator](http://www.x4-game.com/#/station-calculator)
- [Paintmods - X4 Wiki - Egosoft Confluence](https://www.egosoft.com:8444/confluence/display/X4WIKI/Paintmods)

### station plans

- [PHQ Megaplex hexagon V4 (30.03.2023) - egosoft.com](https://forum.egosoft.com/viewtopic.php?t=437848)
- [Drache´s Station Collection - egosoft.com](https://forum.egosoft.com/viewtopic.php?f=195&t=429918)

<style>
h1 {
  counter-reset: h2
}

h2 {
  counter-reset: h3
}

h3 {
  counter-reset: h4
}

h2:before {
  counter-increment: h2;
  content: counter(h2) ". "
}

h3:before {
  counter-increment: h3;
  content: counter(h2) "." counter(h3) ". "
}

h4:before {
  counter-increment: h4;
  content: counter(h2) "." counter(h3) "." counter(h4) ". "
}
</style>
