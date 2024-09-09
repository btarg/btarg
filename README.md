# btarg
<img align='left' height='75' src='https://github.com/btarg/Origami/blob/master/crane.png?raw=true' style='padding-right: 10px;' />

My favourite programming language is C#, and I mostly focus on game development and modding. I code in my spare time to learn as much as I can and to create the best solutions to problems I have with existing software and games.

I also own and operate [the 21st portfolio](https://21stportfolio.com), a student-run literature blog, and I occasionally write poetry and reviews for the site.

<a href='https://ko-fi.com/btarg' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

## Projects

### [Project Requiem (WIP)](https://github.com/btarg/third-person-controller)
Project Requiem is a work-in-progress turn-based RPG made in [**Godot 4**](https://godotengine.org) using **GDScript**. It is heavily story-driven and features an expansive design document with over 6,000 words outlining the game’s intricate narrative and mechanics. [You can explore the design doc here](https://docs.google.com/document/d/1ciNLXNb76iGfoPWgEIhHHFKyTaYyUXYv_RmkQ1yvwhU/edit?usp=sharing).
#### Creating the project
In this project, I make heavy use of **state machines** to manage the gameplay flow. For example:

- **Exploration vs. Battle**: State machines manage whether the player is in exploration mode or engaged in battle.
- **Character Battle States**: During battles, each character has a state machine that determines whether they are attacking, defending, waiting, etc.

While **GDScript** was a new language for me, my previous experience with **C# in Unity** and **AngelScript in Unreal Engine** allowed me to quickly adapt and implement gameplay systems effectively.

The design of my data structures and gameplay flow is informed by previous attempts at creating similar RPG mechanics in Unity and Unreal Engine, as well as working with others (especially the friendly people in the official Godot Discord server) to collect feedback and improve gameplay.

### [ByteReserve](https://github.com/btarg/AWS-Upload) (halted for now)
ByteReserve is a pay-as-you-go, end-to-end encrypted file upload service (similar to **DropBox**, for example). The current code in the repo does not work, as I stopped developing it mid-rewrite.
ByteReserve is my first large-scale full-stack **JavaScript** application.

It uses [Node.js](https://nodejs.org/) on the backend, and [Vue](https://vuejs.org/) with [Tailwind](https://tailwindcss.com/) on the frontend. This was my first time making a dynamic and responsible frontend user experience, but I was quickly able to adapt to using Vue from previous experience writing basic HTML pages for other projects.

The site would encrypt all user-uploaded files entirely within the browser, before uploading to [BackBlaze B2.](https://backblaze.com) **This ensured strict user privacy, and the storage was incredibly cheap.** For further increased privacy, my **PostgreSQL** database would not store any sensitive information about users or files.

Users would be charged hourly based on "credits" that they could top up, rather than monthly out of real money on a card. This would ensure that people would not be charged when forgetting to renew a subscription: an annoyance I have with many other alternative services like Google Drive which I believe to be solved by ByteReserve.

Currently, the project's development is halted. The credits and billing systems are not yet implemented.

### [Origami](https://github.com/btarg/origami) (Abandoned)
Origami is a Minecraft server plugin for the [Paper](https://papermc.org/) platform, which allows for server owners to create more a customised experience closer to that of modded Minecraft, regardless of the players' clients.

I used many tricks and hacks present in vanilla Minecraft code to create custom blocks and items, implementing a system which allowed the server owner to write simple **YAML files** to define custom properties for each item or block.

The plugin also featured [extensive, easy-to-follow documentation](https://btarg.gitbook.io/origami-docs), marking my first time writing proper docs for a programming project. I believe they turned out helpful and well-organised.

Other, more [feature-complete alternatives](https://modrinth.com/mod/polymer) exist now for server-side modding, but I learned a lot about backend and server development.


### [CraftGPT](https://github.com/btarg/CraftGPT) (Proof of concept)
CraftGPT was an experiment with [Langchain4J](https://github.com/langchain4j/langchain4j) and PaperMC. The plugin allows a player on a Minecraft server to speak to a **GPT-powered LLM**, which could execute commands in the game. For instance, the player could ask for "something useful for mining," and be given a pickaxe by the LLM.

The plugin also **observed more general information about the players **in the server: for instance, if that player had asked more generally for "something useful," and they were low on health, they might recieve food or a healing potion to restore it.

Other, better alternatives for this idea exist, however I was **one of the first to implement** this particular idea in code.


### [Twitch Vs Minecraft](https://github.com/btarg/TwitchVsMinecraft2) (Abandoned)
Twitch vs Minecraft is a Minecraft Forge mod which allows a player's Twitch chat to **directly interact with their game** through commands.

It was heavily inspired by other existing projects like [CrowdControl](https://crowdcontrol.live/), but offered the easiest setup out of all available livestream interactivity mods, with pre-defined commands that I programmed myself.

Twitch Vs Minecraft was the project I used for learning Java, and served as a testbed for my Java development skills for a few years while I maintained it. These days there are again more feature-complete and up-to-date alternatives available, but I believe that my mod was the best in the category in terms of user experience (especially its unparalleled ease of use) while I actively worked on it.

## Skills
[![My Skills](https://skillicons.dev/icons?i=github,java,cs,unity,godot,unreal,python,idea,discord,bots,linux,nginx,gcp,ps,md,netlify,powershell)](https://skillicons.dev)

## Contact
You can contact me on [LinkedIn](https://www.linkedin.com/in/benjamin-targett-1298ab29a/) if you are interested in hiring a developer with any of these skills!
