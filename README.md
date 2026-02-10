Here's your tutorial formatted for GitHub markdown:

---

# Initial Launch

You will be prompted with a link to this Tutorial. You can close it.
**Player Name:** Use an identifier other players will see. It must be at least 4 characters long, with no special characters and no spaces.

The first screen displayed is the Characters screen.

**Button - Add New Party:** This is used as your party name. All characters on the same device that share the same party will share gold and items in the stash.

**Popup - Add New Adventurer:** Choose a source for this adventurer.
- **Campaign Starter** starts with one of the 4 pickable Adventurer with the recommended items and disciplines.
- Using the **All options** option, you may pick from every Adventurer card available and will start with nothing.

**Popup - Connection Type (First Character Created):**
This will set your connection type. It can be changed later by clicking the Peer icon > Connection Options > Change Connection.
- **None:** Does not receive or send messages.
- **Host:** A single Host is required to connect all players and will handle all messages between client players.
- **Client:** Everyone other than the single Host should be a Client.

---

# Character Screen

After the initial setup, the Characters screen is used to pick which character to play.

**Gear icon:** Allows for backups (import/export)

**Button - Add New Party:** Allows you to create a new party.

If an adventurer is selected, the button **Add New Adventurer** will be present and allow you to create an adventurer for the current party.

Holding an adventurer allows you to load, export its data, or delete it.

Single press loads the adventurer.

---

# Mission Screen

This screen is divided into 5 sections: Equipped, Carried, Stats, Combatants and Books

## Top Bar

The top bar will always be displayed and shows some important information.
<img width="1200" height="50" alt="topbar" src="https://github.com/user-attachments/assets/89bc4c68-2a36-4ea8-8a55-f107f72d8510" />

**Connection Icon** - Depending on your connection settings, you may see the amount of players currently connected. Pressing on this icon, or a red WiFi icon (in case there was an issue or the connection is stopped) will display some connection options.

**Card Icon** - Here you can draw cards: Combat loot, unique items, monster loot, general items, hidden cards, abraxis and exalted espers. When a card is drawn, you will have multiple options, such as moving it to your pack or stash, redrawing another card (Redraw), getting more info about the card such as rules (Info) etc. If connected, you can share the drawn cards with the other players (Share).
<img width="600" height="270" alt="cardoptions" src="https://github.com/user-attachments/assets/c9b05596-fde6-456c-9249-b01ee88dddb0" />

**Stamina** - Used to track your stamina.

**Hourglass Icon**
- **Refresh:** Refresh will auto unexhaust all cards, give your stamina back and automatically trigger most things. A popup will inform you of what happened, such as Poison damage. You can uncheck things you don't want to apply on the current refresh. It is also possible to disable those triggers in the options.
- **End Encounter:** Will remove the used tokens and also trigger most end of encounter cards. It will split/share the gold between the different players if you wish to. It also clears all combatants in play.
- **Restore:** Does everything a restore will do.
- **Urgency Tokens**

**Gear Icon**
- **Looted Gold:** Here you can add the looted gold during your adventure. This is split when you end an encounter.
- **Add XP:** Allows you to add XP to your adventurer.
- **Current Item Tier:** You can change the current tier here.
- **Campaign**
  - **Notes:** Your personal notes
  - **Adventurers:** Here you can see the current roster of adventurers. You can add some, set as injured or unselectable. You can also change your adventurer here.
  - **Flags:** Allows you to check flags
  - **Achievements:** Allows you to check achievements
  - **Story Unlocks:** Displays all your current story unlocked cards
  - **Sync:** Syncs your data with the other players (story unlocks, flags, achievements)
- **Other:**
  - **Connection:** Same as the connection icon.
  - **Backup:** Allows you to export and import your data.
  - **Sync:** Allows you to sync your campaign info (story unlock, flags, achievement) or all Unlocks (uniques, combatants etc.).

## Bottom Bar

The bottom bar will always be displayed in this screen.
<img width="1200" height="36" alt="Screenshot_20260209_222022" src="https://github.com/user-attachments/assets/aa2b669a-9fb8-455e-af05-ed4373e7999b" />

**Tokens** - Pressing here will show you a list of all tokens. Once at least 1 token is added, a quick list feature is displayed instead, allowing you to change quickly often-used tokens.

**Cast/Conv:** Your current Casting/Conviction dice. Long press allows you to display the bonus source.

**Health/Def/Move/Armor:** Your current stats. Pressing health allows you to change your current HP. Long pressing health, or single pressing on the others, allows you to display the bonus source (Info) or modify the stats temporarily.

## Equipped

Here are shown to your left your disciplines and adventurer abilities.

Next to it are all your equipped items.

Single press on a discipline or item will display the possible options, like exhaust and flip.

More options are available (you can flip all cards there, or add special tokens such as Stupefy or share a card with the other players).

It is also possible to "remove" the card (It will show "Removed" and add no bonus).

An option is also there to send or gain tokens quickly if the card refers to that token. Choosing to send an Intervention will display the list of all the connected players and current allies (command). Same for negative effects and enemies.

Long pressing a card will zoom it and show rules info regarding that card.

## Carried

Here are all consumables carried and items in the Pack.

Pressing a card will show options related to the item, just like with Equipped items. Carried consumables may also be "Used" (Deleted, or flipped if that is how it works).

Long pressing a card will zoom it and show rules info regarding that card.

## Stats

Most of your stats are here. You can press a stat to show the bonus source or add a temporary bonus. Looted gold and XP can also be modified here.

## Combatants

Pressing the small icon on the top right will show you all of the options regarding this section.
<img width="600" height="270" alt="combatantmenu" src="https://github.com/user-attachments/assets/a8ad3d00-ad9f-4f30-92ec-fe9107430968" />

- **Remove [Combatant Name]:** Displayed when a combatant is selected
- **[Combatant Name] (Info):** Displayed when a combatant is selected. Displays the rules of the combatant. Long press on the combatant image also shows this info.
- **Add a Combatant**
  - **Setup Phase:** No variant or alternate. Used during setup.
    - **Base type only:** Only lists the base type of each combatant
    - **Current tier:** Lists all combatants from the current tier and their variants/alternates.
    - **Any tier:** Lists all combatants from any tier and their variants/alternates.
    - After choosing one of the options, you may choose the IDs to spawn and change the tier
  - **Extra Spawn:** Will let you pick the amount to spawn and will spawn variants and alternates following the variant rules for them.
    - **Current tier:** Lists all combatants from the current tier and their variants/alternates.
    - **Any tier:** Lists all combatants from any tier and their variants/alternates.
    - After choosing one of the options, you may choose the amount to spawn, change the possible tier, and uncheck Allow Variations and Alternates
  - **A Boss:** Shows a list of unlocked bosses
  - **A Mimicry:** Shows a list of mimicry enemies
  - **Summon Opposing Esper (Greyed out if no combatant selected):** Used to spawn Opposing Espers.
  - **Unlock:** Unlock a combatant (Hidden cards).
- **Sync:** Allows you to sync your current combatants and command with the other players (in case someone joins late or there is an issue).
- **Add a Command**
  - **A Command:** Shows a list of all hidden cards for command
  - **An Esper:** Shows a list of all Espers

In the combatant main screen, you will have all the combatant names on top. Pressing on it will show its image and all the current figurine HP. Pressing a figure HP (Cave Sickle 1: (6/6)) will allow you to change its Health, add tokens etc. Pressing the '+' next to it allows you to add more IDs for that combatant.

When you kill a combatant, a reminder for Combat loot will popup, when applicable.

Pressing the image in cases where the combatant or command can send tokens will give you a list of potential targets.

In the case of a Command or Esper, a bottom bar similar to your Adventurer bar will be displayed. It allows you to handle tokens, stamina, stats and refresh. The main display's image is divided, allowing you to press and long press single abilities.
<img width="600" height="270" alt="esper" src="https://github.com/user-attachments/assets/f9c2c783-a210-4d45-90de-e0a056372b9a" />

## Books


In the top left, 3 options are present: Rules, Adventure and Mission.

**Rules** allows you to display most rules found in the books. A filter can be used to quickly search the name or text of the rules.

The gear option allows you to change the text size.

**Adventure** allows you to quickly access Sparknotes. A play button can be used to read the sparknotes while you setup or shop around.

The gear option allows you to change the current book, draw hidden cards or change the text size.

**Mission** allows you to see all the missions in the book and also see diagrams. A play button can be used to read the mission's lore and rules while you setup.

The gear option allows you to change the current book, draw hidden cards, use the red Decoder, display Diagrams and also to setup combatants.






To continue...
