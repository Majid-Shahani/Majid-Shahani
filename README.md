<img width="25%" alt="lain-dancing" src="https://media.tenor.com/XLprFoJLe6kAAAAi/lain-serial-experiments-lain.gif" />

> [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&vCenter=true&duration=2500&pause=7500&color=229C07&width=215&height=21&lines=connection+established...)](https://git.io/typing-svg)

## Psyche [About]
Computer engineering student drawn to low-level thinking and high-performance systems. I care more about how something behaves under pressure than how quickly it can be made to work. I like thinking about the physical realities of our hardware and how data flows through the systems.

## Religion [Focus]
Game Engine, Real-time rendering and systems programming, such as:

[user space RCU: Quiescent-State-Based Reclamation in C++23](https://github.com/Majid-Shahani/qsbr-rcu)
- Designed a lock-free read path using generation checkpoints instead of per-access hazard pointers, resulting in near-zero reader overhead.
- Implemented safe memory reclamation by freeing retired values older than the oldest active reader’s checkpoint, resulting in deterministic cleanup without reference counting.
- Built an active/inactive reader state using per-slot flags, resulting in stalled or exiting readers that no longer block reclamation.
- Structured publish() to allocate the retirement slot before swapping the pointer, resulting in a noexcept operation with a strong exception guarantee.
- Specified the concurrency contract for writer and reader threads, resulting in clear usage rules for a library with no runtime misuse detection.

[Game Engine Core](https://github.com/Majid-Shahani/carnival-engine)

### The following are part of [carnival-world](https://github.com/Majid-Shahani/carnival-world/):

[carnival-world: Game Engine Networking Module](https://github.com/Majid-Shahani/carnival-world/blob/main/Networking.md):
- Implemented a session system using clear state tracking for handshake, heartbeat, timeout, and reconnection, resulting in simple and reliable connection handling for real-time use.
- Designed a channel system over UDP by splitting traffic into unreliable, reliable, and snapshot paths, resulting in better control over what needs guarantees and what does not.
- Built a reliability system using sequence numbers and ACK tracking to detect lost packets and resend them, resulting in reliable delivery without using TCP.

[carnival-world: Entity-Component-System](https://github.com/Majid-Shahani/carnival-world/blob/main/ECS.md):
- Engineered Structure of Arrays memory layouts, improving CPU cache locality and enabling predictable large-scale entity update performance.
- Implemented dynamic archetype migration for runtime component add/remove operations, maintaining dense packed storage through structural changes.
- Developed query and iteration systems across matching archetypes, providing efficient read/write access with explicit mutation policies.
- Created dirty-state/version tracking for update-based replication, reducing unnecessary network traffic for infrequently changing gameplay data.

## Distortion [Working on]
A discrete-event simulator that finds bottlenecks in production lines and ranks fixes by the output they recover, built around data-oriented design. Alongside it, a model-checking study of how relaxed the memory orderings of a recent lock-free hazard-pointer list can be.
<br/>
Full stack web, database engines, and Rust in operating systems are on the shelf for now. I’ll be back to them, but not for a while.

## Society
Open to collaboration on graphics, systems programming, engine tooling, or game programming. Anything where creativity in architecture and design, or performance-centric thinking is needed, sounds lovely.

## Love
Video games, especially immersive sims and RPGs. <br/>
Parkour and Fashion. Freedom and self-expression are my beacons. <br/>
Physics Is my first and forever, curious to know how stuff works and make use of it.

## Landscape
<div align="center">

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
<br/>
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
<br/>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Linux](https://img.shields.io/badge/linux-%23FCC624.svg?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

</div>

## Protocol
email: majid.shahani03@gmail.com <br/>
linkedin: [linkedin.com/in/majid-shahani](https://www.linkedin.com/in/majid-shahani/)

> [![](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=4000&pause=5500&color=229C07&random=true&height=21&vCenter=true&width=435&lines=signal+remains+stable...;signal+remains+stable...;signal+remains+stable...;signal+remains+stable...;for+now...)](https://git.io/typing-svg)
