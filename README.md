#Rewriting this b/c why not :eyes:
As you can see, this is a fork of chafla (a.k.a l_u_c_a_r_i_o)'s goPC and no rewrite has been done yet. So go back to the original project page if you are
# goPC
Universal bot, similar to Bill's PC from the /r/PokemonGO discord, and written by `Luc | ルカリオ#5653`.
Designed out of demand for a similar sort of solution in smaller servers, where users want a no-fuss solution that adds roles based on Pokemon GO teams. Designed to be light, and shouldn't really interfere with anything. Doesn't log anything, either.

Requires at least Python 3.5.1 be installed, as well as the latest version of discord.py.

__Note that this is **not** designed to be an extremely multi-functional bot like BooBot.__ It's designed for a niche, and should work alongside existing bots.
If you want to use this bot's code, *please please please* don't name it the same thing that mine is set to (currently goPC)


# Current features:

* Ability to add roles based on a simple command, `%team [team name]`, where team name is Instinct, Valor or Mystic.
Other aliases do exist, such as the simple colors; red, blue, yellow. However, **the user must input Valor, Instinct or Mystic**.
Users would, for example, type:
`%team Valor`
to join Team Valor.

The server requires roles that correspond to the team name, and are formatted as shown above.

**Team aliases are a planned feature, but not a first-release feature.**

* Ability to whitelist certain channels for assigning %team.

* Team requests can be sent through PMs, and have a selection menu if you share more than one server.

* Ability to create a set of empty template roles (no permissions) that can then be configured manually.





# Roles Required:

* Manage Permissions: Required in order to add roles to members.

* Read Messages: Required in order to respond to commands.

* Send Messages: Also required in order to respond to commands, obviously.



# Planned additions

At the moment, I'm going to go for an early release with the sole functionality of adding team commands, but there are some features I'd like to implement in the future.

* Aliases for team names.

* Ability to use different role lists than just the Pokemon Go team list, so as to make the bot useful in other applications.

* Perhaps adding some other commands that are a bit more fun. __This isn't really the intention of the bot, though, and I probably won't be adding many fun commands.__ So don't pester me about it, please. :P

A lot of these hinge on me making adaptability for each specific server, but hang in there, because it should be coming eventually.
