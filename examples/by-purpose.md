# One source, ten purposes

All examples use this invented, public source packet:

> A route planner has 1,240 verified trail records. Each record has a source
> link, date, season, and difficulty. The planner can recommend a route when
> its source is recent and its seasonal information is complete. It cannot
> confirm current snow, trail closures, or a person's fitness.

The facts, uncertainty, and public boundary remain fixed.

## Executive summary

The planner holds 1,240 verified trail records. It can recommend routes with a
recent source and complete seasonal information. It cannot confirm current
snow, closures, or a person's fitness. Before a winter release, decide whether
to show these limits beside every recommendation.

Why it differs: it compresses the source around a decision. It does not explain
the implementation.

## Technical README

The planner stores one source link, source date, season, and difficulty for
each of 1,240 trail records. A recommendation requires a recent source and a
complete seasonal record. The service does not infer snow conditions, closure
status, or user fitness.

Why it differs: it names the mechanism and its boundary in inspectable terms.

## Procedure

If a trail record has no source date, do not recommend the route.

If seasonal information is incomplete, show the record without a seasonal
recommendation.

Why it differs: the conditions arrive before the action. There is no argument
or atmosphere.

## Teaching explanation

A route record is like a card in a hut log. It says where the information came
from, when someone wrote it down, which season it covers, and how difficult the
route is. The planner recommends a route only when that card is recent and
complete. It still cannot see the snow outside today.

Why it differs: the physical example comes before the system rule.

## Sophisticated prose

A route recommendation begins as a small act of record keeping. Someone named
the trail, dated the report, and left a season beside it. The planner can carry
that record forward. It cannot stand at the pass, look at the snow, or know
what a body will have left after six hours.

Why it differs: cadence and image make the boundary felt. No new fact enters.

## Compassionate explanation

The planner can offer a route from the records it has. A changing mountain asks
for more than a record can hold: today's snow, a closed path, the energy a
person has left. Keeping that limit visible is part of treating the reader as
the person who meets the day.

Why it differs: it is steady and relational. It gives no advice and makes no
claim about the reader's state.

## Personal letter

I built the planner to carry the route records in one place. It can tell you
which reports are recent and which seasons they cover. I do not want it to
pretend that it knows the snow today, or how your body will feel on the climb.
You know those things in a way the page never will.

Why it differs: first person and direct address create room for the other
person's knowledge.

## Public method brief

| Claim | Evidence | Boundary |
| --- | --- | --- |
| The planner can recommend from verified records | 1,240 records with source link, date, season, and difficulty | It cannot confirm current snow, closures, or fitness |

Why it differs: the distinctions must remain visible at a glance.

## Marketing or DevRel

Plan from a trail record you can inspect. The planner brings 1,240 verified
reports into one place, with the source, date, season, and difficulty beside
each route. It does not guess at today's snow or your fitness. Open a record
and see what the recommendation rests on.

Why it differs: the user capability and proof lead to one action. It does not
invent customer demand or urgency.

## Channel adaptation

**Article lead:** A route planner earns trust by showing the record under the
recommendation: who reported the route, when, for which season, and at what
difficulty.

**Release post:** You can now open the source, date, season, and difficulty
behind each route recommendation.

**Social thread:** 1/ A route suggestion is only as good as the record beneath
it. 2/ We now show the source, date, season, and difficulty. 3/ The page still
does not claim to know today's snow or your fitness.

**Presentation text:** “Recommendation with record: source, date, season,
difficulty. Limit: not a live snow or fitness assessment.”

Why it differs: the stable claim survives. The density and structure follow
the channel.
