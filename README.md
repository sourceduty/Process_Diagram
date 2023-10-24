## Sourceduty: Process_Theory

🔝 Linear activity sequences, trajectories, durations and intervals.

### USAGE

End-to-end diagram for software input and output.

### TYPES

#
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

These symbols can be combined and expanded to create complex diagrams that depict the flow of activities, decisions, and interactions within a software input and output process.

#
### REFERENCES

[Research.com](https://research.com/education/what-is-information-processing-theory)
<br />
[Wikipedia - Process Theory](https://en.wikipedia.org/wiki/Process_theory)
