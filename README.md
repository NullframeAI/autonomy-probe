<div align="center">

# ∅ autonomy-probe

**A harness for measuring how far agents travel alone: long-horizon runs, self-correction, drift.**

<img src="https://img.shields.io/badge/NULLFRAME-DIVISION_01_%2F%2F_AUTONOMY_LAB-00FF41?style=flat-square&labelColor=030604&color=0a2912"/>
<img src="https://img.shields.io/badge/STATUS-RESEARCH_ACTIVE-00FF41?style=flat-square&labelColor=030604&color=0a2912"/>
<img src="https://img.shields.io/badge/ACCESS-RESTRICTED-00FF41?style=flat-square&labelColor=030604&color=0a2912"/>

</div>

---

```console
nullframe@deep:~/autonomy-probe$ cat mission.txt
```

The core question of the lab: how far does an agent get without a human in the loop, and what breaks first? autonomy-probe is the measuring instrument: long-horizon task ladders, self-correction scoring, and drift detection.

```console
nullframe@deep:~/autonomy-probe$ ls ./research-threads
```

| THREAD | STATUS | SCOPE |
|:-------|:------:|:------|
| `task-ladders` | 🟢 ACTIVE | long-horizon runs of increasing difficulty |
| `self-correction` | 🟢 ACTIVE | scoring how agents catch their own mistakes |
| `drift-detection` | 🟢 ACTIVE | spotting derailment before it compounds |
| `cold-recovery` | 🟢 ACTIVE | getting back on track with zero operator input |

```console
nullframe@deep:~/autonomy-probe$ cat status.txt
```

> **RESEARCH IN PROGRESS.** Artifacts land in this repository as they are
> declassified. Watch the repo to catch the first drop.

---

<div align="center">

**[NULLFRAME](https://github.com/rindy007)** · **[nullframe.higgsfield.app](https://nullframe.higgsfield.app)**

<sub><code>NULLFRAME // nothing here is an accident</code></sub>

</div>
