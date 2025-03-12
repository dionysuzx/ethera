## Introduction

Ethera is a town square for Ethereans. The inspiration behind Ethera is to create a platform that is better for coordinating knowledge across the Ethereum ecosystem. The status quo is that all information comes from "Crypo Twitter" (also known as CT). The problem with Twitter (referring to X as Twitter) is that Ethereans must be on it for work (to get useful industry information and dialogue), but the platform has so much fighting and noise.

The reason for the fighting and noise is simply because Twitter optimizes for attention in their algorithm, and specifically around rage-baiting (anything that gets a rise out of people).

Thus, Ethera wants to provide a better coordination zone for Ethereans to talk about EIPs, future upgrades, and other critiques and criticisms about Ethereum. It does not intend to be "all positive news" but the most meaningful place for people to socially interact with knowledge to help push the Ethereum ecosystem forward as much as possible.

Ethereum is an interesting project because it is something we all own and engage with together. We need a central commons / town square.

## Technology

The technology we are using is:

- Farcaster: Farcaster allows us to bootstrap a social network and inherit all the technology that they have been working on.
- Krome stack: This is mainly Svelte/Tauri, so we can create a mobile app experience.
- Farcaster frames: Allow us to implement Polis, something we'll talk about.

## Features

Here are the features of Ethera:

1. A scrollable home feed for Ethereums to engage and talk about things, which embeds some Polis voting.
2. A dashboards / metrics page for the most popular statistics related to Ethereum.
3. A futarchy page / section to further educate the populace.
4. A bot account (codenamed "Plato") that pulls from Eth Research, Eth Magicians, ACD calls etc. to inform the communiy of what is going on, and calls to action.

### Crazier ideas..?

5. A farcaster frame that allows users to comment on Eth research / Eth magicians / GitHub without an account on those platforms necessarily (remove any barriers to communication), and also allow anonymized posting / voting (which is somewhat verifiably human)
6. A reward tier / badges / levels for how much you are engaging in the platform. This could allow other communities to reward these community members.

## POC

Here is the POC we are currently working on:

- Login: User connects via Farcaster (e.g., wallet signature).
- Feed: 5-10 sample posts about Ethereum, pulled from Farcaster or hardcoded.
- Post: User types a message, clicks “Post,” and it appears in the feed.
- Vote: One post has a Polis-style poll with 3 buttons (e.g., Yes/No/Maybe).
- UI: A simple, clean layout (e.g., white background, purple accents).
