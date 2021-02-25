We characterize two common failures modes that arise in inefficient task operation. To personify these modes, imagine two characters: Schmidt and Saposcat. Schmidt is the epitome of a productive, efficient human resource whereas Saposcat is mediocre and unconscientious. With these two characters, we introduce some conceptualizations of productivity sinks --- operating modes characterized by resource leakage/misallocation --- and propose some mitigation strategies.

**Two kinds of failure**

Let us name these two failures $$\alpha$$ and $$\Alpha$$ (from "acedia" meaning "without cares") --- typifications erosive to productivity (assuming some reasonable measure of productivity).

To borrow from probability theory, scale and location are parameters that describe the spread and center of a distribution; inappropriate settings of scale and location impede the efficacious completion of tasks, and subsequently, of goals (a goal necessitating completion of multiple tasks). $$\alpha$$ concerns inefficiencies of "scale" while $$\Alpha$$ concerns suboptimal estimates of "location" in the performance of tasks that advance some goal or objective. $$\alpha$$ usually manifests when too much energy of focus is invested into a task; $$\Alpha$$ appears when the current task is misaligned or irrelevant to the intended goal.

Saposcat will succumb to $$\alpha$$ and $$\Alpha$$ if he focuses too narrowly or deviates too far from the assigned task, accumulating penalty after penalty by selecting tasks with a low likelihood of furthering his objectives. On the other hand, Schmidt is more assiduous in investing only the required amount of resources to a task while ensuring the current task is the most appropriate in the current operating context.

$$\alpha$$ represents a failure to efficiently utilize the resources allocated to a task; $$\Alpha$$ represents a failure to properly shift between levels of operation or abstraction, leading to suboptimal task prioritization. Both $$\alpha$$ and $$\Alpha$$ interact and feedback --- $$\alpha$$ can lead to overexertion and the depletion of resources through burn-out or scope creep, which leads to $$\Alpha$$ through burn-in (*i.e.* a "sunk cost"; a failure to exit) and decision fatigue --- reinforcing inefficiencies into habits and blindspots.

Schmidt is careful to consider the scope and impact of a task lest he waste energy in pursuit of marginal gains. Schmidt also adjusts his tempo like a conductor to fit the mood of his work and groups similar pieces together --- cueing them in a way that logically flows from one to another, avoiding jarring transitions. Conversely, Saposcat is haphazard with the baton: fiddling it from one hand to the other, constantly dropping and picking it up, using it to scratch his back and pick his nose. 

A table comparing $$\alpha$$ and $$\Alpha$$.

|            |                          $$\alpha$$                          |            $$\Alpha$$            |
| :--------: | :----------------------------------------------------------: | :------------------------------: |
| Parameter  |                            Scale                             |             Location             |
|  Concerns  |                   Focus; detail; burn-rate                   |      Scheduling; allocation      |
|  Examples  | Burn-out; [stalls](https://en.wikipedia.org/wiki/Analysis_paralysis); scope creep | Burn-in; sunk costs; saturation  |
| Indication | Lose of perspective; [fatigue](https://en.wikipedia.org/wiki/Decision_fatigue) | Complacency to plateaux; erosion |



**Mitigation strategy**

So, how might we mitigate these two failures, $$\alpha$$ and $$\Alpha$$, so that Saposcat becomes more like Schmidt?

For $$\alpha$$, one can reduce expenditure of resources (focus, energy, time, *etc.*) mainly through [satisficing](https://en.wikipedia.org/wiki/Satisficing) to smooth out step functions into ramps:

* **Adjust zoom/window levels**

  * Routinely affirm appropriate scope and cost for task completion
  * If possible, delegate to subject matter expert and defer low-priority tasks
  * Linearize and ignore higher-order complexity
  * *Skimming* --- triage relevance before investing resources into processing *e.g.* read title; then read the table of contents; then jump to a specific chapter; at any time, stop reading if deemed not sufficiently pertinent

* **Stop multi-tasking** 

  * Preserve/prioritize resources for tasks which have highest chance of advancing goals
  * Minimize overhead from context-switching
  * *Indexing* --- if not immediately relevant, index and reference for later retrieval

* **Avoid fancy toolsets** --- tools are extensions that must be regularly maintained and exercised

  * A beginner should not learn to drive in a racecar without first learning the fundamentals of maneuvering and steering a less powerful engine
  * Additional complexity and functionality must be justified against the marginal opportunity cost to acquire, learn, and maintain

  * Simple tools are easier to maintain, practice, and fix into the proper state of readiness; a dull knife or rusted pan is worthless to a chef during the dinner rush --- *mise en place*
  * Leverage creative constraints so as to not spoil yourself (remember that others have done more with less than what you already have; do not blame your tools)



For $$\Alpha$$, strategies are higher-level actions:

* **Iterate faster** --- defer abstraction to prefer shape over texture

  * Increase [iterations over entire cycle](https://en.wikipedia.org/wiki/OODA_loop); 
    * Familiarize end-to-end process to prevent blindspots 
    * Incorporating external feedback from Reality to heightens awareness and ability to shift between  modes
  * [No premature optimization](https://en.wikipedia.org/wiki/Program_optimization)
  * Fast baseline to assess difficulty and chokepoints/bottlenecks

* **Delineate shifts and practice shifting**

  * Acknowledge separate modes with names/characterization *e.g.* "editing", "sketching", "refactoring", "exploring", "theorizing"
  * Batch/coalesce similar tasks together *e.g.* shallow administration work such as checking emails once a day 
  * Think of tradeoffs *e.g.* greedy versus optimal searches, function versus detail, prototype versus state-of-the-art

* **Set breakpoints** --- use dead space to debug and review and recalibrate

  * Have predefined completion criteria and exit conditions
  * Check in at fixed intervals progress and estimates with instrumentation and logging

  * Pause and reflect on the counterfactual/hypothetical (*e.g.* consider trade-offs between feasibility/impact vs. effort/risk)
  * Restarts or reboots or rewrites may be necessary if too much cruft has already accumulated

* **Keep few rules and simple processes** --- it is harder to subtract than to add; keep things simple enough for a mentally disadvantaged Saposcat

  * Fewer rules are easier to follow, remember, and ingrain into habits/mindsets
  * Beware the "meta-processes"; avoid excessive/intricate planning/tracking
  * Systems tend towards disorder over time
    * all processes compound and propagate their errors but complexity can hide longer symptoms of decay and staleness
    * as much as is possible, limit dependencies and coupling



**Beyond $$\alpha$$ and $$\Alpha$$**

To eat our own dogfood, let us zoom out of our constructed dichotomy. Like Saposcat and Schmidt,  $$\alpha$$ and $$\Alpha$$ are total fictional concepts, invented by us in order to illustrate and [operationalize](https://en.wikipedia.org/wiki/Operationalization) recognizable patterns. Abstractions can quickly devolve into distractions, and the reader is well advised to ignore any or all of our advice (including this).

We intended to describe two general patterns that indicate breakdown in systems; systems that, as they grow in complexity, must more efficiently consume resources and produce control signals to influence their operation in constrained and dynamic environments. 

We speculate that complex systems inherently benefit from acquiring/selecting more efficient and adaptive behaviors. An efficient system can be represented compactly, which facilitates its continued existence and propagation. For example, the genomic sequence is comprises four nucleotide bases and the few characters in the latin alphabet is flexible enough to create complex systems of communication and culture. Adaptive systems that are more robust to a wide dynamic range of environmental conditions are likely to have elements of redundancy or techniques for error correction in lossy communication channels. These attributes serve to preserve the system for the continuation of its evolutionary lifetime. Additionally, adaptivity of activation thresholds can reduce friction, allowing methods to escape local optima (saturating plateaux and basins) to find a better operating point on the Pareto front. While we make no normative claims about productivity or efficiency being inherently "positive", we generally observe that communication and synchronization within many varieties of complex systems are correlated with adaptive, regulating behaviors.



**Aside on procrastination loops**

Procrastination is often perceived as a detriment to productivity or as a flaw in character morale or social mores. However, we view procrastination as a complex feedback mechanism --- stemming from sensations of pain and exacerbated by normative pressures of modernity and technology. Fundamentally, procrastination is a psychological aversion or avoidance to assignments in favor of more immediately gratifying activities. The lack of disciplined self-control is only a proximal cause or procrastination. Several factors, external to individual control, also contribute. The modern individual is inundated with stimulus and access to distractions which were unfathomable to the prehistorical individual. Widespread availability to pathways to short circuit reward systems have led to several consequences such as increased prevalence of attention deficit, dysthymia, and anxiety. Rapid technological advances and integration have led to an exponential increase in information, decision, and opportunity. Everyday, we bear additional cognitive overhead of choosing among many potential options. While we may rely on some mental heuristics and leverage external tools, our processing capabilities are fundamentally limited; too much novelty saturates our senses; too many decisions lead to indecision. We become fatigued and default to distraction and entertainment --- the product of a hyper-capitalist society of consumption and growth --- which diminishes the productivity of the individual. 



Finally, ensure all tasks (and goals) are: 

1. **Concrete and actionable**
2. **Realistic and achievable**
3. **Bounded and measurable.**

