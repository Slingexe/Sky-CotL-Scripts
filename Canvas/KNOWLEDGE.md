# Knowledge Base

## Heart Trade Config
**"Heart Trade Config"** is a setting that lets you send hearts to selected friends at a cost of three candles each. This is similar to sending hearts through the constellation but is automated each time you run **"Send Gifts"** in AutoWax.

This feature can be convenient if you frequently gift hearts to someone.

> [!NOTE]  
> Unlike the name suggests, this setting does not guarantee that
> you will receive hearts in return. Recipients must still choose to
> send hearts back to you when they come online.
> 
> Do not add people to the config unless you are certain about how it
> works, as this function will also consume your candles.


## Collect WL
Each winged light in Sky has its own unique codename or `id`. Here's what they look like:

> l_CandleSpace_0,l_Credits_0,l_Dawn_0,l_Dawn_1,l_Dawn_2,l_Dawn_3,l_Dawn_4,l_Dawn_5,l_Dawn_TrialsAir_0,l_Dawn_TrialsEarth_0,l_Dawn_TrialsFire_0,l_Dawn_TrialsWater_0,l_DayHubCave_0,l_Dusk_0,l_Dusk_1,l_DuskEnd_0,l_DuskGraveyard_0,l_DuskGraveyard_1,l_DuskGraveyard_2,l_DuskGraveyard_3  
`-----rest trimmed for brevity-----`

And the list just keeps going! This means that you need to specify the particular wing `id`s you're after. Rest assured, there's no need to memorize a single thing.

We've got a wing list ready for you to grab and pop right into the WL collector prompt: [237_wing_code_thatskymod.txt](https://raw.githubusercontent.com/thatskymod/Sky-CotL-Scripts/main/Canvas/Misc/237_wing_code_thatskymod.txt).

You’ve got a couple of options:
- Copy the entire list to clipboard and press **"Paste"** in the WL collector.
- You can also use your browser's download function to save it as a local file and later load it into AutoWax.

Once you’re all set, hit **"Run"** to finalize the collection. For the increased wing level to take effect, please restart your game.

## Reset Collected WL

> [!WARNING]
> Winged Lights collected from **Spirits** are **permanent** and cannot be reset. They may **seem to disappear** when you take damage from poisoned water, krill, or shards, but will eventually resurface once you are reborn.
> This is a technical quirk on TGC's end and not something that mods can access or fix.

LibSmite did a great job of warning users about this beforehand: https://github.com/thatskymod/Sky-CotL-Scripts/discussions/80#discussioncomment-9480710. Langit also recently implemented a similar warning (see https://github.com/thatskymod/Sky-CotL-Scripts/discussions/111#discussioncomment-10983087).

In short, resetting spirit wings currently isn't possible with the tools available to us.

## Outfit Visibility

Are the spells, outfits, and props activated through mods visible to other players nearby?

**No**. These customizations are visible **only to you**.

This was once possible but has since been patched. From a technical standpoint, the server now mandates that you **own** an outfit (i.e., have it officially in your inventory) for it to be visible to other players. This is a technical limitation beyond our control. If the server-side ownership verification fails, other players will see you wearing the default outfits (starter mask, onion hair, brown cape). They might even observe your character having broken legs. Here's an example of what this might look like: https://www.youtube.com/watch?v=ZZBRWp0zhwE

Therefore it is generally not recommended to use this type of tweak in the presence of other players. It clearly reveals that you have acquired your appearance by means you should not have.

## Sheet Music

Music for Sky consists of files in the *.json or *.txt formats, often referred to as skysheet files. You can find them on various platforms, including Telegram chats and Discord servers.

Notable examples include:

- **AutoWax gb (Telegram)**  
https://t.me/+UW1yzZp-SWY0NDcy

- **SkyAutoMusic (Discord)**  
https://discord.com/invite/ab8JCnb

- **Sky Music Library (Web)**  
https://sky-music.github.io/
