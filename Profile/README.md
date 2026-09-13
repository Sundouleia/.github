### Created by players, for players. Made for longevity, security, safety, and consideration of the future ahead.

Sundouleia is a Community-First, Sync-Second plugin, prioritizing community health and growth as a center point over datasync. 
```
https://raw.githubusercontent.com/Sundouleia/repo/main/sundouleia.json
```

## Why Try Sundouleia?
- Join Sanctions, our flagship attraction for the plugin. They are communities that behave like a Discord, have **no user cap**, and are designed to help venues grow and stay engaged with their audience.
- Sanctions can have Announcements, Alerts, Embedded Links, an internal Chat, and a SanctionSync you have full management over.
- Create over 50 roles, and assign or revoke over 15 distinct permissions.
- **Enjoy our custom internal actor handler, minimizing redraws.**
- Updates are streamed with deltas, allowing updates to occur almost instantaneously.
- **Server-Side BC7, BC5, BC4, BC3, BC1 Texture Compression** to help reduce lag in large gatherings.
- Enjoy full profile customization: every text, font, color, position, scale, drop shadow, radius, border, and padding can all be customized by you.
- Create your own gradients, shapes, and paths for your profile, letting your flair shine.

## About us
Following the events that transpired after the Mare shutdown, it is important to remember that whenever major platforms fall, opportunists rush to fill in the gap. These people take advantage of those in fear, panic, and desperation to be loud, make quick solutions, and a quick rush to fame.

But as Floof/DarkArchon & Ottermandias reminded us, those who rush to fill these gaps are inherently untrustworthy. That we need time to let the dust settle, and give time for a solution to arrive that is not made with a short sighted vision. True safety, trust, and long-term stability cannot be rushed, for it come to those who wait.

At the end of the day, we’re all in the same boat. Placing too much trust in someone who doesn’t consider the broader impact of their actions puts everyone at risk. One misstep, whether it is a tool that goes too far, too public, repeats past mistakes, or becomes unstoppable, invites harsher action from SE. This is not just about features or syncing. It is about protecting the foundation that keeps our boat afloat.

### This is what drives Sundouleia.
Sundouleia took inspiration from mares tech stack and identified ways the service as a whole could be improved. It had to be remade from the ground up, pivoting to a new architecture for its vision to be fulfilled.
This new structure prioritizes micro-optimizations, efficiency, effectively instant response time, minimal redrawing, and near limitless scalability for all of its features.

## Support
If you want to learn more, see visual guides, report issues, or claim an account, Join the Discord here: https://discord.gg/QJy4zTqpMD

## Our Features and Design Choices
- **Custom file transfer service**  
  - Uses our own sharded file transfer service that simplifies the file transfer logic used previously by Mare. This removes a significant amount of overhead and results in faster transfers with fewer moving parts.
  - File uploads / downloads are processed and applied dynamically, while other data is applied immediately, reducing perceived delay from others and appearing instantanious.
- **Lightning-Fast Updates**  
  Data Updates can be distributed to others as fast as **150ms**, routing deterministic updates over the servers in a manner that avoids bloat as the userbase scales.
- **Live Data Updates**  
  Pair updates modify actors internally when possible, allowing changes to apply immediately without forcing redraws.
  > *This avoids the rapid flashing that commonly occurs when others adjusts advanced material colors or other mod setting updates.*
- **Server-Side File Compression**
  Uploaded textures are automatically compressed server-side, lowering your VRAM usages without impacting your performance. (Supports BC7, BC5, BC3, BC1, applied where best fit)
- **Connection States**
  Multiple connection modes (`Try-On`, `Streamer`, `Connected`) control how data is sent, received, and applied, rather than relying on a single connected/disconnected state.
- **Loci Custom Status Management**  
  - Includive custom status control
  - Inclusive status locking  
  - Inclusive target application for statuses on controlled and uncontrolled actors
  - Permission-based control over application and removal
  - __If permission is granted,__ you are able to choose from a pairs statuses when applying, or apply from your own.
- **Command-based interaction**  
  - All major components of Sundouleia have integrated command support that let you automate almost every context menu and keybind interaction through the UI.
  - All commands make use of `CLI` (Command-Line Interface) formatted parsing, allowing for flexibility and a wide range of arguments/paramaters/flags.
- **CkCommons UI Framework**  
  - A handcrafted UI wrapper over ImGui, accessing top level, native, and internal methods to redesign existing UI methods with stylization overhauls.
  - Blends graphic UX design with unique widgets for a more modern UI design.
  - Little to no performance impact with optimized logic, giving you no concern for high drawframe times which could otherwise impact FPS
- **Dynamic Draw System (DDS)**  
  - A custom rendering system for pairs, groups, and folders, with support for customization, context menus, and keybind-driven interactions.
  - Versitile Drag-Drop utility, with support for multi-selection, including across different folders.
  - Every part of the DDS can have their color, icon, or text customized at will without sacrificing performance.
- **Request system**  
  Radar and overworld support, bulk accept/reject, temporary or permanent pairing, attached messages, anonymous identifiers, and privacy throttling.
- **Layered complexity**  
  The UI/UX is designed to be digestable at face value, while holding advanced options available for those that want deeper control.
- **Custom Color/Style/Theme Support**  
  Fully configurable styling through CkCommons, including an integrated editor and theme support.

## Why Trust us?
Ultimately, whether you trust us is your decision.

That said, anyone who used GSpeak knows we’ve been operating a server-based plugin for around over a year now that interacts with a the client in ways that, if misused, could force a wide range of actions.

Despite this level of access, throughout its entire time online we’ve maintained strong security practices, addressed issues quickly, and avoided abuse wherever possible.

We are deliberate about what we add. Features are only implemented when we’re confident they will not create future security risks or privacy concerns. We consistently prioritize user privacy and long-term impact over rushing functionality.
