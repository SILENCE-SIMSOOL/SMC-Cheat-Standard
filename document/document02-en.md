# Standards for Skyblock Hacks

Before we begin, please note that this document is based on the author’s personal thoughts and opinions. Feedback and constructive criticism are always welcome at any time.
In the future, your feedback will be reflected, and if deemed reasonable, the content will be continuously revised based on your suggestions.
Both Skyblock players and mod developers are welcome to contribute. Please share your opinions through a direct message on Discord at SimSool!

## Messy Hypixel Rules
Hypixel has a somewhat vague yet clear rule: "Boundaries of allowed and prohibited actions are defined, but actions beyond those boundaries are not the platform's responsibility to enforce."
This means that although an action may not violate the rules, a user can still be banned, with the associated risk falling entirely on the user.
Such rules, which shift responsibility in this way, are rare in other games and impose significant challenges on players.

Most Skyblock players use various Skyblock mods.
이때 그 외의 범위에 속하는 기능들이 매우 많으며 허용 여부에 대해 물어보아도 처벌을 책임지지 않는다고만 말합니다.  
One might ask why not stick strictly to allowed mods? The issue lies in the disparity of experience; users who do not use such mods cannot enjoy the same functionalities and opportunities as those who do.

## The Misguided Perceptions of Hacks in Korea

Since its early days, the culture of fairness and equal opportunity in gaming has shifted at certain points, transforming into a system where individual players wield disproportionate power. This shift led to widespread discontent among players, and eventually, the justification and normalization of cheating began.

Most players, including those reading this, are not entirely “legit.”
Let’s take the most essential and commonly used mods, like Skytils, as examples.
If asked whether ESP is a cheat, everyone would answer that it is.
This is explicitly stated in Hypixel's rules as a clear cheat.
Then what about mods that show the target block of Etherwarps, check completed tasks on the 4th device, display specific terrains in Crystal Hollows, or show map names?
These are mods everyone uses as if they’re normal.

- The Etherwarp mod scans blocks beyond our sight and determines whether if you can Etherwarp onto that block or cannot.
- Device-checking mods, terrain-revealing mods, or map name mods function the same as X-ray.
The feature of scanning visible blocks and that of scanning invisible ones is entirely the same.
Thus, scanning visible blocks is equally problematic, but these mods go further by scanning invisible blocks.
However, the standard for cheats is usually not based solely on logic or clear criteria, but is determined by the thoughts and consensus of the community.
For this reason, these mods already violate the rules, but they use methods that make users mistakenly believe they are not cheats.

The problem of X-Ray hack lies in the fact that it is telling the information of blocks that cannot be seen.

For example: 

  The block I’m about to ether warp at glows.
    ㄴ Even the blocks that cannot be seen will be scanned.

  While doing the arrow device, it marks what block I have shot. 
    ㄴ It marks even without looking at that place.

  I found the 지형, it would be convenient to remember the coordinates of this place.
    ㄴ It only shows "지형 found" when you come near it, so it doesn't look like a hack. However, mods like Soopy that scan the entire map from the start are considered hacks. 단순하게 핵의 강도가 다른거지 Skytils의 기능만 레짓인게 절대 아닙니다.
    
This is not the only function; puzzle solvers and most features simply collect information about about what's around the user.
It doesn't matter if the information given to you is visible to you or not.
They work the same even if you cannot visually see the information given to you by the mod.
However, the most important part for users is what you see, which is why mods like Neu show the location of Pest mobs only when visible.
But as mentioned, this feature cannot check if something is on the screen, so it’s simply an ESP mode.

If you consider Skytils as a legit mod, these features should all be considered as legit features:
- Using Ender Pearls even if you are standing right next to a block
- Scanning the map from the start and telling the room informations (FunnyMap)
- Showing team member or boss locations (ESP)

## How to properly use mods.

Then, does that mean I shouldn't use Skytils? Of course not.
Hypixel has changed to allow 퍼즐같은 mods specifically for SkyBlock, and Skytils mods have been indirectly designated as allowed mods.
Then, to put it again, unfortunately, these mods are also outside the regulations that Hypixel have set, and even though they have not been classified as hacks, the user must bear the risk of being banned. 
Then, I will let you know the features that are safe and cannot lead to a ban even though they fall outside the scope of the regulations

  - All features related to ESP / XRay
  Minecraft already sends information about nearby entities and blocks from the server side.
  But the game client system you use only shows what you see.
  When you mine a block in front, it’s not a new block being generated behind, but one that already exists, and your client   just shows the next one after the previous block disappears.
  This means that the server has already sent the information, and the client already received it, and obviously knows it,    but pretends like it doesn't.
  If you use a reach hack, it sends a request to the server saying you hit an enemy that’s 10 blocks away.
  Then the server will notice the request, which is a hit from 10 blocks away, and obviously detect it as a hack.
  그런데 이미 나한테 준 정보의 1만큼을 보던 100만큼을 보던 서버한테 보내는 정보나 요청은 없습니다.
  Other games have different methods and use anti-cheat feature on their PCs, checking the user's client, but          Hypixel can only check from the server side, so ESP or XRay mods that only operate on the client side are not detectable.
  (For example: Player ESP, Mob ESP, map mode that scans rooms and shows names, 지형 name display mods, device solver mods,   and secret location mods. The feature that shows the location of secrets is not considered ESP, while the feature that      scans the room to identify which specific room it is, falls under the category of ESP.)

  - 강제 엔더펄 기능
  Skytils already has a mode that prevents flower-type weapons from being planted when right-clicking on dirt blocks. Ender   Pearls are just the exact same feature.
  In Minecraft, there are many events that happen when you right-click, and if you cancel all events when you right-click     an item and intentinally use only “Use Item Ability”, you can use the weapon's abilities, but cancel other events such as   placing blocks.
  Ender Pearls are also made with exactly the same code, and simply because it was developed first in hack mods, it gets      recognized as a hack.
  여기서 많은 분들이 이런 주장을 합니다. 엔더펄은 사용 불가능한 부분에서 사용되는데 분명하게 불공정한 모드 아니냐?
  If you say that, flowers also shouldn’t be usable when clicked on dirt until another flower is given, but only users who    use unfair mods can use it.
  Also, if you hold a sword or potion and press both left and right click simultaneously, left-click takes priority, so the   right-click gets ignored and will mine blocks immediately.
  However, animation mods prioritize the right-click first, preventing blocks from being mined.
  엔더펄을 던질 때 실제로 그곳에서 던지지 못하는 것이 아니라 블럭설치 이벤트가 우선순위에 있어서 그렇습니다.
  If this is still a problem, you should not use block-hit animation mods either.
  Also, these functions can easily be detected and blocked by Hypixel. They just need to check if a target block exists       when a player right-clicks with an ender pearl in hand.
  However, there have been no bans for this feature so far, and it should not be considered a ban reason based on the         precedent of block-hit mods.

(Next are mods that I am reluctant to claim that those are not fully hacks.)

  - Ghost Block / FunnyMap 맵 수정 modes have the same function. The server clearly sends information that there’s a stone       in front of me, but those mods make us think that it’s somehow a wood.
  However, the truth doesn’t change. It’s wood from what I see, but if you mine it with an axe, it would break extremely      slow, and if you click or render the block again, it will change. In reality, it’s stone, but it only appears as wood       only on my screen. So, it’s generally a function that doesn’t provide any benefit.
  If you change it to a invisible block, you could use the XRay effect, but as I said, you are already using mods that        classified as XRay. Also, ghost blocks cannot originally be passed through.
  You can easily test this in single-player. Minecraft has a feature that checks this, and Hypixel either mistakenly turned   it off or it became a critical bug while developing the whole new block mining system.
  But as we know from updates or alpha servers, it can be blocked, but it remains because of user protest to fixing the bug.
  The reason these mods work is that Hypixel actually allows them.
  In optimizing mods like FoamFix the ghost block bug can also happen, but they are not considered hacks.
  It is because originally, ghost blocks do not provide any benefit.

(Next are mods that are definitely hacks but are mistakenly thought to be legit.)

  - SA Terminal: For this to be legit, clicking one item should only click one slot.
  SA's method is very similar to an auto terminal.
  The terminal's unique click cooldown and ping cause a delay until the next click.
  If that time is 0.2 seconds, and you press four buttons in 0.2 seconds, SA clicks the four buttons using the auto           terminal feature.
  You can click every 0.2 seconds, and since you need to click four, the auto terminal macro will finish in 0.8 seconds.
  Clearly, I clicked within 0.2 seconds, but after 0.2 seconds and up to 0.8 seconds, even though I’m doing nothing, SA       automatically clicks.
  This mod is often mistaken for zero ping, but the false screen that SA shows you is zero ping, and it doesn't actually      solve the ping at all.
  The reason many users misunderstand this is because while they are solving a puzzle on the screen displayed by SA, the      mod is solving it using the auto terminal, which makes it appear like it’s not affected by the ping from the terminal.
  In reality, you are not solving the terminal. Even though you’ve solved the puzzle on the screen shown by SA, the auto      terminal hasn’t finished the terminal yet, so you can often see it completing a little later.
  Since it clicks at the earliest possible time for the next click, it retains the characteristics of the most bannable       auto macro.
  This mod was initially introduced as a legit feature, deceiving users, and many people were banned during a ban wave        because of it.
  Afterwards, it was claimed that users with high ping wouldn’t be banned, and still, many top players confidently use SA     mode, claiming it’s legit.
