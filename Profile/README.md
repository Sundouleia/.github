![Banner Image](https://raw.githubusercontent.com/Sundouleia/repo/main/Images/Banner.png)
```
https://raw.githubusercontent.com/Sundouleia/repo/main/sundouleia.json
```
### Made by players, for players. Designed for longevity, security, safety, and consideration for the future ahead.

Following the events that transpired after the Mare shutdown, it is important to remember that whenever major platforms fall, opportunists rush to fill in the gap. These people take advantage of those in fear, panic, and desperation to be loud, make quick solutions, and a quick rush to fame.

But as Floof/DarkArchon & Ottermandias reminded us, those who rush to fill these gaps are inherently untrustworthy. That we need time to let the dust settle, and give time for a solution to arrive that is not made with a short sighted vision. True safety, trust, and long-term stability cannot be rushed, for it come to those who wait.

At the end of the day, we’re all in the same boat. Placing too much trust in someone who doesn’t consider the broader impact of their actions puts everyone at risk. One misstep, whether it is a tool that goes too far, too public, repeats past mistakes, or becomes unstoppable, invites harsher action from SE. This is not just about features or syncing. It is about protecting the foundation that keeps our boat afloat.

## This is what drives Sundouleia.
To create a plugin that has longevity, security, safety, and consideration for the future ahead. Sundouleia is a fully independant project constructed from scratch.

Sundouleia puts a heavy focus on reducing overhead, improving responsiveness, and giving the client more direct control over how data is transferred, applied, and managed.
Most systems were built or reworked with the goal of minimizing unnecessary redraws, avoiding excess synchronization, and keeping behavior predictable as scale increases.

## Our Features and Design Choices
- **Custom file transfer service**  
  - Uses our own sharded file transfer service that simplifies the file transfer logic used previously by Mare. This removes a significant amount of overhead and results in faster transfers with fewer moving parts.
  - File uploads / downloads are processed and applied dynamically, while other data is applied immediately, reducing perceived delay from others and appearing instantanious.
- **Deterministic updates**  
  Data Updates can be distributed to others as fast as **150ms**, routing deterministic updates over the servers in a manner that avoids bloat as the userbase scales.
- **Live Data Updates**  
  Pair updates modify actors internally when possible, allowing changes to apply immediately without forcing redraws.
  > *This avoids the rapid flashing that commonly occurs when others adjusts advanced material colors or other mod setting updates.*

- **Connection States**  
  Multiple connection modes (`Try-On`, `Streamer`, `Connected`) control how data is sent, received, and applied, rather than relying on a single connected/disconnected state.
- **Official Supported Moodles Integration __(You can finally apply Moodles to pairs!)__**  
  - Whitelisted support for applying Moodles to pairs
    > *Granted to Sundouleia from years of trust. Thank you Kawaii and Glyceri* 🙏  
  - Sundouleia owns ephemeral Moodle data for reliable synchronization
    > Ephemeral means moodles applied to others by Sundouleia cannot be overriden, and ensure proper sync.   
  - Permission-based control over application and removal  
  - __If permission is granted,__ you are able to choose from a pairs moodles when applying, or you can apply from your own.
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

