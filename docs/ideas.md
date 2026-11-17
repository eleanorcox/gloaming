# Ideas

Every idea so far, each with the smallest version worth trying. Sizes are rough guesses: **S** is a few days, **M** is a week or two, **L** is a month or more.

## Summary

| Idea | Size | Needs hardware |
| --- | --- | --- |
| A field of drifting lights | S | no |
| Flashing in sync | S | no |
| Responding to sound | S | microphone |
| Responding to people | S, reusing the aquarium's movement input | webcam |
| Depth: near and far lights | M | no |
| Projected on a wall or ceiling | S | projector |
| Projection-mapped onto real things | M | projector |
| A TouchDesigner version | M | Windows or Mac (unchecked) |
| A night of them: dusk to dark | M | no |

## A field of drifting lights

Hundreds of small soft glows wandering slowly over a dark scene, each flashing now and then. The baseline every other idea builds on.

- **Smallest version:** 300 points of light drifting with gentle random wandering, each blinking on its own timer, on black.

## Flashing in sync

Some fireflies flash together: a few kinds gather in thousands and end up blinking as one (*Photinus carolinus* in the Great Smoky Mountains is the famous case; unchecked). It is usually modelled with **coupled oscillators**: each firefly has an internal clock, and seeing a neighbour flash nudges its own clock a little forward. Started out of step, the whole field gradually falls into time. Mathematicians call one version the **Kuramoto model** (unchecked).

- **Why it is good:** it is equations making something beautiful, as in the aquarium. Watching a field drift into sync is a slow, satisfying thing to see.
- **Smallest version:** a field that starts out of step and syncs over a minute, with a slider for how strongly they nudge each other.

## Responding to sound

- **To music:** the beat nudges every firefly's clock, so the field slowly falls into time with the music rather than flashing mechanically on each beat.
- **To a room:** quiet brings them out; a loud noise makes them all go dark at once, then they come back one by one.
- **Smallest version:** brightness follows the microphone's loudness.
- **Unknown:** picking out the beat reliably from a microphone in a noisy room.

## Responding to people

The aquarium already has movement input: the webcam spots anything moving and the fish react. Here, fireflies could part around someone walking past, or gather where someone stands still. Cupping your hands could hold a firefly, using the aquarium's hand tracking.

## Depth: near and far lights

Lights at different distances: far ones tiny and sharp, near ones big and blurred (**bokeh**, the soft discs out-of-focus lights make in photographs). Grass and tree silhouettes against a last bit of sky.

## Projected on a wall or ceiling

The aquarium's display window and corner correction already make this easy to try. Lying under a ceiling of fireflies.

## Projection-mapped onto real things

Fireflies among real plants, a hedge or a garden: the projection is masked so the lights only appear on or around the real things.

## A TouchDesigner version

**TouchDesigner** is a tool for live visuals built by wiring boxes together on screen instead of writing code, popular for projection and installation work. Gloaming is a good first TouchDesigner project because it is small. TouchDesigner runs on Windows and macOS, not Linux (unchecked), so this needs another machine.

## A night of them: dusk to dark

The piece runs through an evening: the sky going from deep blue to black, a few fireflies at first, then many.
