> **Terms of Service**

> **Discord's Terms/Guidelines**\
> Since Pogger is a Discord bot which follows it's API ratelimits and ToS. All rules considering it's terms and guidelines also apply on Pogger's ToS.\
> https://discordapp.com/terms \
> https://discordapp.com/guidelines

> **Restricting Members**\
> Requiring members to pay real money to connect to the voice channel that members use to create lobbies in the guild `is not` allowed. If you're reported doing this, we're allowed to revoke access for that guild to use Pogger. Keep in mind requiring anything else like voting/bumping the guild or getting a certain level/rank in the guild `is` allowed.

> **Channel Renaming**\
> Purposefully joining guilds to create lobbies and name them inappropriately is not allowed. Even though administrators have access to deny which names they don't want to be allowed to use when naming channels, it's still not allowed as it's almost impossible to think of every inappropriate word and words similar to it. There is also a limit to how many denied renames there can be. So, if you're individually reported for doing this, we're allowed to revoke access from  your account.

> **Zombie Lobbies**\
> Since the internet isn't always perfect especially when you're dealing with external sources. There can be situations where a lobby is not deleted when everyone leaves it. When this occurs please feel free to create a support ticket in the [Pogger Support](https://discord.gg/wsW2bGDC2H) discord server to report the problem. What were currently doing to conquer this problem is were quering all the active lobbies on a loop and checking if either the corresponding text or voice channel is not in the bots memory or if the voice channel's size is 0. This seems to work 99% of the time because channels are deleted before they're removed from the database. The reason why this is discussed is because using this bot means you may sometimes have a problem with a random lobby not deleting. Keep in mind that this would be true with any other join to create discord bot.

> **Requiring Administrator**\
> Pogger does require administrator permissions to operate anything in the guild. It'll always deny further action even if the action doesn't require administrator permissions. Technically a bot should never require administrator permissions for anything but currently this is the easiest way to prevent Pogger from making invalid HTTP requests. In the future when Pogger is updated to only [Node's](https://nodejs.org/en/) standard library. It'll only require certain permissions since depending on owners giving a bot administrator permissions is extremely unrealistic. In the mean time we can assure you that giving Pogger administrator permissions is completely safe. The only way to give someone access to Pogger is through a token which isn't accessible to anyone except the Developer.

> **Cooldowns**\
> There is currently 3 different basic cooldowns Pogger has to add a security layer to prevent spaming Discord's API. The first one is a 3 second cooldown that is unique to each command a member uses. We don't want to make a 3 second cooldown for each member on all commands unless we see an absolute reason to do so. Using the same command with Pogger in less than 3 seconds is unnecessary but is necessary when using different commands. The second cooldown is a renaming a channel more than 2 times in less than 10 minutes. This is a unique ratelimit that only applies to changing channel names and topics for Discord's API and is not from Pogger. The last one is a 5 second cooldown that applies when members join a voice channel that is used to create lobbies. If you try to rejoin that channel in less than 5 seconds then it'll ignore you and you'll have to leave and rejoin again when the 5 seconds is up.
