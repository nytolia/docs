---
description: Overview about the Claim System
---

# 🎩 Claim System

#### Basic Commands:

* **/claim \[\<radius>]**\
  This command allows a player to claim a territory. By default, it claims the chunk you are currently standing in. Optionally, you can provide a radius to claim multiple chunks around your location.
* **/claim main \<claim-name>**\
  Opens the main graphical user interface (GUI) for managing the specified claim.

#### Settings and Members Management:

* **/claim settings \[\<claim-name>]**\
  Opens the settings GUI for the specified claim. Use this to adjust various configurations for your claimed land.
* **/claim members \[\<claim-name>]**\
  Opens the members GUI for managing who has access to the specified claim. You can add or remove players, or manage permissions.

#### Chunk Management:

* **/claim chunks \[\<claim-name>]**\
  Opens the chunks GUI for a claim, allowing you to view and manage the individual chunks within the claim.
* **/claim add \[<\*|claim-name>] \<player>**\
  Adds a player to your claim. Use `*` to apply this to all your claims, or specify a claim name. If no claim name is provided, it will apply to the claim you are standing in.
* **/claim remove \[<\*|claim-name>] \<player>**\
  Removes a player from your claim, using similar logic as the `/claim add` command.

#### Ban and Kick Commands:

* **/claim ban \[<\*|claim-name>] \<player>**\
  Bans a player from entering your claim. Use `*` to ban from all your claims, or specify a claim name.
* **/claim unban \[<\*|claim-name>] \<player>**\
  Unbans a player, allowing them to enter your claim again. Use `*` to unban from all your claims or specify a claim.
* **/claim bans \[\<claim-name>]**\
  Opens the bans GUI, where you can view and manage banned players for the specified claim.
* **/claim kick \[<\*|claim-name>] \<player>**\
  Physically kicks a player out of your claim. You can use this for specific claims or all your claims by using `*`.

#### Claim Ownership and Teleportation:

* **/claim owner \[<\*|claim-name>] \<player>** \
  Transfers ownership of the claim to another player. Use `*` to transfer ownership of all your claims.
* **/claim tp \<claim-name>**\
  Teleports you to one of your claims by providing the claim name.
* **/claim list**\
  Opens a GUI that lists all of your claims for easy access and management.

#### Spawn, Name, and Description Management:

* **/claim setspawn**\
  Sets the spawn location within your claim.
* **/claim setname \<old-claim-name> \<new-claim-name>**\
  Changes the name of one of your claims.

#### Claim Merging and Chunk Management:

* **/claim merge \<claim-name> \<claim-name>**\
  Merges two claims into one. Both claim names must be provided.
* **/claim addchunk \<claim-name>**\
  Adds the chunk you are standing in to an existing claim.
* **/claim delchunk \<claim-name> \<chunk>**\
  Removes a chunk from your claim. Specify the chunk in the format `world;x;z`.

#### Global Claim Management:

* **/claims**\
  Opens a GUI listing all claims on the server, including those of other players.
* **/unclaim \[\<claim-name|\*>]**\
  Deletes a claim. You can specify a claim name or use `*` to unclaim all of your territories.

***

This system provides full land ownership control with extensive options for management, member permissions. Enjoy using the **Claim System** to secure your territory and enhance your server experience!
