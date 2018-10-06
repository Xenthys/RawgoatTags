## Info

Simulate the kind of messages sent by people who attempt to be original in their DM advertisements.

## Code

```
{source:dmads}{choose:Hello|Heya|Hi {nickname}|Hi}! {choose:I see that you just joined {server_name}; join our affiliate server!|Do you wanna join a very {choose:cool|awesome|amazing|active} server?|You should {choose:come join|check out|be a part of|hang in|chill with us in} our {choose:awesome|amazing|incredible|stupendous|sweet} server!|Join us!}
{set:emote|{choose:⚖|🏁|🏆|✌|🐰|🍀|✨|🍪|🎱|🏅|🎧|👾|🎮|🎬|🚧|💿|🛡|⚔|💈|📥|🛒|🔞|🔱|⚜|🔰}}
{get:emote|1} **{choose:Awesome|Epic|Ultimate|Official|Pro|Perfect|Top|Incredible|Friendly} {choose:Gamers|Anime|Fun|Weebs|Pros|Youtubers|Minecrafters|Lovers|Friends|Players|Roblox} {choose:Official|United|Inc|Verified|Hacks|NSFW}** {get:emote|1}
{set:spacer|{choose:📍|✅|✔|🔹|🔸|▶|+|>}}
__{choose:We have|What we have|Features|We have everything|Here's what we do}:__
{if:{random:0|3}=0||{get:spacer|1} Active community!
}{if:{random:0|3}=0||{get:spacer|1} {choose:Daily|Weekly|Monthly} events!
}{if:{random:0|3}=0||{get:spacer|1} {choose:Daily|Weekly|Monthly} giveaways!
}{if:{random:0|3}=0||{get:spacer|1} Open staff position!
}{if:{random:0|3}=0||{get:spacer|1} Lots of gamers!
}{if:{random:0|3}=0||{get:spacer|1} Cute anime!
}{if:{random:0|3}=0||{get:spacer|1} NSFW!
}
{choose:Join today|Come join now|Join|Quick, join|So what are you waiting for}, we have over **{random:0|5000}** {choose:members|gamers|pros|users|people}!
```

## Example

`!dmads`

Hello! You should chill with us in our sweet server!

:shopping_cart: **Perfect Roblox NSFW** :shopping_cart:

__What we have:__  
:small_orange_diamond: Active community!  
:small_orange_diamond: Weekly events!  
:small_orange_diamond: Lots of gamers!  
:small_orange_diamond: NSFW!

So what are you waiting for, we have over **4125** gamers!

## Credits

Created by jagrosh#4824  
Adapted by Xenthys#0001  
