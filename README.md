# Discord.Py-Hy-Dice-Roller
A non-interactive dice roller for Discord.py written in Hy. 


**Setup**
1. Have a Discord.py bot (Quickstart available at https://discordpy.readthedocs.io/en/stable/quickstart.html)
2. Assuming you're using the minimal quickstart bot, place the cog in the same folder as your bot.
3. Add ```import Hy 
      import COG_dice_roller
      client.load_extension('COG_dice_roller')``` somewhere in the code of your bot.
4. Run the minimal bot.
5. Type ```!rd XdY ``` or ```!roll_dice XdY``` (where X is the amount of dice and Y is the type of dice) in the Discord server chat where the bot is setup to see the dice roller in action. 
