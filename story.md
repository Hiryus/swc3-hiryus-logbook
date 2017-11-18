# Prolog

In a world far far away, the competition between The Titanium Creeps and the Dancing Squirrels has
evolved into a global and brutal war for the domination of the sector. During precisely 30 days,
the conflict raged on until one of them got finally defeated and flew in the hope of finding a
better place the settle.

This logbook was written by hiryus and describe the main events of the war.


# Day 1 (2017-11-17)

I chose to spawn in E11S7 for two reasons. First, it was easy to defend with small exits. Then, it
also had lemergium which I planned to use for boosting my healers.

My start was a bit slower than some other AIs because I was not remote mining, but I was not
worried: contrary to others, my rooms plan to get to RCL3 and build a tower on their own before the
safe mode drops. Thus I didn’t get bothered when other remote rooms got attacked.

At RCL3, I sent a claimer to E11S9. I was planning fast expansion while my enemies didn't have too
much power. As my first room was still under safe mode, the new one was basically defenseless, but
the energy invested was minimal.

SteveTrov decided to attack my workers while they were trying to build the spawn. His creeps
murdered them, removed the spawn construction site and sat there waiting for reinforcements. But
they never came. My AI didn’t bother to spend energy for the room, knowing that a safe mode would
be available later.

The attack was expected, but it was not a reason to acknowledge it. I decided to launch a
counterattack on E13S6, SteveTrov’s first remote mine. E11S7 spawned three attackers composed of
ATTACK and MOVE parts only. After some pathfinding approximations, they entered SteveTrov’s room
and began disturbing the remote mining operation.

![disturbing remote mining operations](img/1.disturbing_remote_mining_operations.gif)

While I was doing a quick update to include one HEAL part to my attackers body, SteveTrov reacted
and fixed a few bugs in his defenders behavior: they began kiting quite effectively. It was time to
stop the attack and plan something else.

![SteveTrov kiters in action](img/2.SteveTrov_answer_healers_rangers.gif)

I changed my target and my attackers started heading towards E13S3, Kasami’s remote mining room. I
was interested in blocking the room because it was also giving Kasami access to his second remote
mine:

![Kasami remote mines](img/4.kasamis_remotes.png)

While first successful, the attack was repelled a few hundreds ticks later by Kasami’s rangers which
were most of the time successfully kiting my melee attackers (though, they failed sometimes).

![Attacking Kasami](img/3.attacking_kasami.gif)

I decided to stop the hostilities for the night and went to sleep, hopping to see my second room
(E11S9) alive and healthy later in the morning.

By this time, the map situation looked like this:

![Map situation on 2017-11-17](img/Situation_2017-11-18_00-00.png)


# Day 2 (2017-11-17)

I woke up late and checked the situation. My second room was indeed healthy and had built a tower
during the night, good. E11S7, my main room was also RC4 and ready for another day of massacre.

First, I decided to claim E15S9. It was well protected in a dead-end and I needed the Oxygen it
contained. Despite completely messing up the process (forgetting to generate structures layouts and
destroyed the spawn twice…), the room finally started to work.

![E15S9 building up](img/6_E15S9_building_up.png)

SteveTrov tried another time to step in, but my AI just activated safe mode and didn’t care much
about it. In the meantime, I sent a few attackers to E15S8 where he was building his second room. I
killed the first creeps and construction sites, but he sent a defensive squad which was way more
powerful than my creeps to stop it. That was a draw I guess.

![Map situation on 2017-11-18](img/Situation_2017-11-18_12-50.png)

When coming back to E11S7, I got the unpleasant surprise to find two large invaders messing up with
my main base operation… Unfortunately, they were quite effective and I had no way to clear them. I
had to be patient and wait for them to eventually die from old age.

![Invaders messing up](img/4.invaders.gif)

When my room got back to nominal performances, I began sending creeps against RediJedi, helping
geir1983 to clear some rooms. Cooperation payed off and we destroyed two rooms and geir1983 was
also applying a lot of pressure against RediJedi main base.

![Cleaning rooms together](img/cleaning_rooms_together.gif)

After some time, I stopped the attack, letting my ally containing the threat. Instead, I began an
attack against ricane’s first expansion. Unfortunately, Atavus got paid by the other team or
something: he was shooting my creeps before they get a chance to reach their targets.

But on tick 61747, SteveTrov launched a brutal attack on my main base which had still no walls.
Four rangers with heal parts stepped in, which was probably more than what my lone tower could
handle. Fortunately, they broke formation and the tower finally killed them:

![SteveTrov's attack on E11S7](img/7_stevetrovs_attack.gif)

Still, I was not really confident about the next attack. In parallel, he was also sending similar
squads against my remote mines for some time. My AI was ignoring them, sending remote miners back
in when the attacker were timing out.

As I needed to get out for a bit, I told my AI to claim E13S9. I wasn't expecting it to last as
E15S9 was still using a safe mode, but who knows ?

When I came back, E13S9 was indeed collapsing, spawn destroyed and room back to level 1. However,
E15S9 was dead too! It looks like the room didn't developed as expected and my earlier fails didn't
let enough time on the safe mode timer to get to RCL3 before SteveTrov attack.

![The situation when I came back](img/situation_2017-11-18_20-30.png)

The good news though is that Atavus came back, whitelisted me and did a good job at arrassing
Ricane's colony which was struggling to survive.
"So, what should I do now?", I asked me. My attack code clearly needed improvements and I was
probably not going to kill anything at this point. Fair enough, I could still play defensively.

First of, I sent a claimer to E6S9 from where Nyoom was expelled by Geir1983 earlier. The room is
further away from SteveTov who was my main problem so far and it had a nice Oxygen source which I
was lacking after E15S9 loss. Also, the room has two sources and the controller nearby each other
which is always nice.

![E6S9 auto-generated layout](img/E6S9_layout.png)

Then, I start working on proper attack code. I was far from the end when bonzaiferroni and Geir1983
asked for coordinated attack against RediJedi who was the only one of his team remaining in the
left sector.

We had already harassed him for hours, but his tower was still up and shooting. Geir1983 and
bonzaiferroni packed an impressive amount of creeps (6 creeps squad for bonzaiferroni!). Except
bonzaiferroni who had a RC5 room, we were all RCL4 which is not the easiest way to take a tower
down.

On my side, I spawned my usual melee attackers and sent them in E6S3 which RediJedi was using to
back up his main room (his main only had one source and was struggling with energy). In the
meantime, bonzaiferroni and Geir1983 sent their squads in the E5S3, the said main room.

After a quick one-sided match, my creeps shut down mining operations in E6S3. Our squads arrived in
E5S3 a bit later. They stood up while the tower was unleashing its mighty shots at blank range and
survived the onslaught without a dent in their painting. Shortly, the tower ran out of energy and
we released the squirrels. They made a short work of the remaining creeps and structures, sacking
everything.

While everyone was watching the fight, I also sent another attack team sneaking behind enemy lines
towards wtfrank second room. That was a 9 rooms trip between source keepers and hostile rooms, but
they actually did it to my own surprise.

![The attack path](img/9958421.png)

There, they didn't find much resistance. The room had no tower and by the time defenders came in,
the spawn was destroyed without anyone trying to stop my creep. All creeps and structures followed
shortly.

![The glorious march to the spawn](img/315165841651.gif)

I kept my creeps in the room to prevent rebuilding. wtfrank sent several vagues of defenders in the
form of three kiters with heal parts. They were much less effective than SteveTov ones though and
struggled to repelled my creeps. I'm not sure why, but they usually stayed by the edge of the map,
entering and leaving without adding much damage to my creeps.

![squirrels dancing while wtfrank creeps are entering and leaving the room](img/1012185.gif)

After that, it was clearly time to get some sleep and I left the game in my AI hands for the night.

![Maps situation](img/situation_2017-11-19_00-50.png)
