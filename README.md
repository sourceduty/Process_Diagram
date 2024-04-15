![Process Diagram](https://github.com/sourceduty/Process_Theory/assets/123030236/a42a22dc-0b99-4783-ab0a-fb40940841cd)

[Process Diagram](https://chat.openai.com/g/g-BKPxbMYJD-process-diagram) is a specialized AI designed to help create diagrams that represent processes, sequences, and trajectories in software operations. It uses specific symbols to clearly depict various stages and aspects of these processes. This includes different types of processes like preprocess, midprocess, postprocess, and many others. Symbol Diagram focuses on the graphical representation of these operations, making complex software operation flows easier to visualize and understand, but it doesn't provide interpretations or explanations of the processes themselves.

***

<details><summary>Process Types</summary>
<br>

1. Batch Processing
2. Real-time Processing
3. Interactive Processing
4. Multithreading
5. Multiprocessing
6. Time Sharing
7. Distributed Processing
8. Parallel Processing
9. Sequential Processing
10. Transaction Processing

<br>    
</details>

<details><summary>Process Symbols</summary>
<br>

These symbols can be combined and expanded to create complex diagrams that depict the flow of activities, decisions, and interactions within a software input and output process.

### Process (→)
A single process, represented by an arrow (→), signifies a linear progression from one step to the next.
```
Example: 0 → 1 → 2 → 3 → 4
```
This means that the process starts at step 0, moves to step 1, and then to step 2.

#

### Multiprocess (⇄ ⇅ ⇆ ⇇ ⇈ ⇉ ⇊)
A multiprocess involves multiple parallel activities, and it's represented using various symbols. The specific symbol denotes the synchronization or interaction between these activities.
```
Example: 0/0 ⇄ 1/1 ⇉ 2/2
```
This means there are three parallel activities (0, 1, and 2), and the symbols indicate how they interact. In this case, ⇄ suggests they interact closely, while ⇉ indicates a more separated interaction.

#

### Preprocess (↝)
A preprocess is an initial step before the main process, often used for data preparation or setup.
```
Example: 0 ↝ 1
```
This means that step 0 is a preprocessing step that leads to the main process at step 1.

#

### Midprocess (↯)
A midprocess symbolizes intermediate steps within the overall process.
```
Example: 1 ↯ 2
```
This represents an intermediate step occurring between step 1 and step 2.

#

### Postprocess (↦)
A postprocess is a step that occurs after the main process, often used for finalization or cleanup.
```
Example: 4 ↦ 5
```
This means that step 5 is a postprocessing step following step 4.

#

### Reprocess (↺)
Reprocess indicates that a step is being revisited or iterated upon.
```
Example: 3 ↺
```
This means that step 3 is revisited for reprocessing.

#

### Alternating process (⇄)
An alternating process involves steps that alternate or switch between different paths.
```
Example: (3 ⇄ 4)
```
This represents a situation where the process can alternate between step 3 and step 4.

#

### Subprocesses (⇢)
Subprocesses represent a hierarchical structure, where a main process is broken down into smaller subprocesses.
```
Example: 0 ⇢ 1 ⇢ 2 ⇢ 3
```
This signifies that there's a main process (0) that is divided into multiple subprocesses (1, 2, 3).

#

### Process interception (↗ ↙)
Process interception symbols indicate branching or decisions within the process.
```
Example: 2 ↗ 3 ↙ 4
```
This suggests that at step 2, the process can either move to step 3 or step 4 based on a decision.

#

### Optional process (↷)
An optional process is a step that may or may not be executed, depending on certain conditions.
```
Example: 3 ↷
```
This implies that step 3 is optional and may or may not be included in the process.

#

### Joint process (↭)
A joint process symbolizes the convergence of multiple paths or activities into a single path.
```
Example: (3 ↭ 4)
```
This represents a point where multiple activities (3 and 4) merge into a single path.

<br>    
</details>

<details><summary>Data Backup and Recovery Process Example</summary>
<br>

1. Preprocess: Check if backup is needed (↝).
2. Parallel Process: Back up databases and user files simultaneously (⫸).
3. Process: Verify integrity of backups (→).
4. Conditional Process: If verification fails, reprocess backup (⇏).
5. Reprocess: Redo backup process (↺).
6. Optional Process: Notify admin if multiple failures occur (↷).
7. Postprocess: Log completion (↦).

Diagram:

```
↝ Check backup needed ⫸ [Back up databases ⇆ Back up user files] → Verify backups ⇏ {If fail} ↺ Redo backup ↷ Notify admin (optional) → ↦ Log completion
```

<br>    
</details>

<details><summary>Process of Elimination</summary>
<br>

The "Process of Elimination" is represented by a sequence of steps starting with identifying potential candidates. These candidates are then evaluated based on specific criteria. As part of a divergent process, each candidate is subsequently processed individually. The results from each are reviewed, culminating in a final decision. This methodical approach helps in systematically narrowing down options to reach a definitive conclusion.

```
Start → Identify Candidates → Evaluate Criteria → Apply Criteria (⇛) → 
Candidate 1 (↦) → Candidate 2 (↦) → Candidate 3 (↦) → 
Review Results → Final Decision
```

<br>    
</details>

<details><summary>Super Mario Process Example</summary>
<br>

The process diagram for the Super Mario video game captures the essential gameplay loop, starting from the initial game launch to the decision to proceed to the next level or replay the current one. The game begins with the player starting up and selecting a level. Once a level is chosen, the main gameplay segment, labeled as "Play Level," unfolds through several subprocesses. These include navigating the terrain, where the player moves through the level layout, encountering various enemies in alternating patterns, and collecting essential items like coins and power-ups. Optionally, players might pass checkpoints that save their progress. Towards the end of the level, there might be a boss fight, represented as a process interception, which the player must overcome to complete the level. After defeating the boss or reaching the level's end, the game displays results and rewards, followed by a decision point where the player can choose to advance to the next level or replay the current one, illustrating an iterative nature of gameplay. This diagram effectively outlines the dynamic and interactive elements of the Super Mario gameplay experience.

```
Start Game (↝) → Select Level (→) → Play Level (↯)
  ↳ Navigate Terrain (⇢) → Encounter Enemies (⇄) → Collect Items (⇢) → Checkpoints (↷) 
  ↳ Level Boss (↖) → Complete Level (↦) → Results (↦) → Next Level/Replay (↺) → [back to Select Level (→)]
```

<br>    
</details>

#
### Related Links

[Research.com](https://research.com/education/what-is-information-processing-theory)
<br />
[Wikipedia - Process Theory](https://en.wikipedia.org/wiki/Process_theory)

***
Copyright (C) 2024, Sourceduty - All Rights Reserved.
