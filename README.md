# LethalCompanyMods
Mods for the game Lethal Company (LC)

# Current Ideas
1. Infinite Sprint <br>
   _Allow the player to sprint, jump, etc. infinitely without draining their stamina bar_
3. Toy Microphone <br>
   _Create a new scrap that, when equipped, makes the mic audio of the player wielding it to sound like it is coming out of a toy (echo) microphone_
5. New Hazards <br>
6. New Enemies <br>

# Current Status
## Infinite Sprint
Following https://www.youtube.com/watch?v=4Q7Zp5K2ywI, I was able to create my first mod to the game by allowing the player to spring infinitely without draining their stamina bar. This was done by constantly updating the game to set the sprint meter of the player to 1f (the max value).
This was a super fun, interesting, and educative intro into modding for LC and in general. Completing this mod made me excited to push my own skills to higher levels and explore modding other areas of the game.
## Toy Microphone
I currently have a working beta version of the toy microphone with the majority of its functionality. I created a model in Tinkercad and have it added to the game with proper basic interactibility such as being added to the scrap spawning pool, picking up, dropping, fixed weight, and a fixed range of monetary value.
I still need to implement the audio distortion effect when having the toy microphone equipped, which will hopefully make your voice sound like it is going through a toy microphone.
My current ideas for implementing this are to either:
1. Create two walkie talkies that are in the location of the toy microphone for audio input and output. This would allow the player to hear their own voice which I feel like would be a cool benefit for this method
2. Looking through the skinwalker mod (https://thunderstore.io/c/lethal-company/p/RugbugRedfern/Skinwalkers/) to see if RubbugRedfern's methods of having enemies record and replay player mic audio could be a good route. So far, this route seems to not be the best for my mod since the Skinwalker mod records and plays back short audio snippets instead of recording and transmitting audio directly.
  
## New Hazards
Yet to be implemented

## New Enemies
Yet to be implemented


# Helpful Resources
MrMiinxx's series on modding Lethal Company: https://www.youtube.com/watch?v=eXA60ZWMI4M&t=0s
PuggersXD_'s video on creating custom scrap in Lethal Company: https://www.youtube.com/watch?v=JLogNjv_VCU
