# `log.info("Hello world, this is M1N3R.")`
I'm a Splatoon addict who also cobbles together random tools from time to time to help make my life easier.
I also publish those tools here from time to time in the hopes that they can make yours easier too.
It can also ease the mind to know that my applications won't go spying on you. Have a look around--the proof is in the ~~pudding~~source code.

## 👨‍💻 What am I up to?
### Rewriting Kolkra
The [Splatfest server](https://discord.gg/cs42uFePRw)'s old/current Kolkra bot, under the unfulfilled codename [splatfest-queue-system](https://github.com/m1n0rm1n3r/splatfest-queue-system), never got to reach its full potential thanks to a clunky codebase.
I'm rewriting it from scratch, migrating from [Pycord](https://github.com/Pycord-Development/pycord/) to [discord.py](https://github.com/Rapptz/discord.py), from [SurrealDB](https://github.com/surrealdb/surrealdb) to [MongoDB](https://github.com/mongodb/mongo), and in general moving over to better-supported, more stable rocks to build my new house ~~of cards~~ upon.
The new Kolkra bot's components may also become parts of other server-specific bots, and even a public one in the future! 👀

## 💬 How to get in touch with me?
### Discord for fastest response, email may also work
I'm almost always active on Discord, so if you need a somewhat quick response, that's the place to get it--even if it's just to draw my attention to an email you sent me. Please don't waste my time, and read [this](https://nohello.net) (flashbang warning btw) before sliding into my DMs.
Email may also work to drop me a line if Discord's a no-go, and I'll get to it if/when I catch a glimpse of your message while rummaging through my inbox for a 2FA code, verification link, or what-have-you.

## 🔜 What am I planning?
### An as-of-yet unnamed SurrealDB ODM
SurrealDB is one of the coolest databases I've ever seen.
I'm thinking about creating a strongly-typed ODM for SurrealDB on top of [Pydantic](https://github.com/pydantic/pydantic), in a similar vein to [Beanie](https://github.com/roman-right/beanie) (my new favorite data modelling library for MongoDB, which I'm using in Kolkra-NG) and [SQLModel](https://github.com/tiangolo/sqlmodel).
First problem is...I don't have a good name for it that wasn't already yoinked on PyPI. Drop me a line if you have any ideas. 🤔

## 📚 What am I learning?
### Nix and NixOS
[Nix](https://nix.dev) is probably the best POSIX package manager out there, with both a positively massive official repository that even gives the AUR a run for its money, and a fully declarative package management paradigm (like NPM, Cargo, Poetry, etc.), as opposed to the imperative paradigm (`sudo pacman -S firefox` and all that jazz), which lets you do some really cool stuff.
[NixOS](https://nixos.org/) takes the declarative design of Nix and applies it to the entire system. I've been playing around with it off-and-on in a virtual machine, and I've installed Nix on my current Pop!_OS system to try and familiarize myself with Nix (the Turing-complete functional programming language that Nix, the package manager, is built on top of) and get the beginnings of a NixOS config together, so I can hit the ground running when I finally take the plunge.
Once I do get things squared away, I'll think about publishing my config as well!


<!--
**M1N0RM1N3R/M1N0RM1N3R** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
