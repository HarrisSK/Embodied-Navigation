# Embodied-Navigation
A list of papers and relevant materials on Embodied Navigation

## Scope

This repository focuses on papers related to:
- language-grounded navigation
- Object-goal navigation
- vision-language navigation (VLN)

This repository particularly distinguishes between:
- methods that rely on prebuilt global maps
- methods that use only egocentric observations at test time
- hybrid systems combining VLM reasoning with planning/control

### 1. Global-map-based navigation
Methods that first build a global semantic map / visual-language map / scene graph, then perform language grounding and planning.

- [Point2Graph: An End-to-end Point Cloud-based 3D Open-Vocabulary Scene Graph for Robot Navigation](https://arxiv.org/abs/2409.10350)[[project](https://github.com/zimingluo/Point2Graph)]

### 2. Egocentric policy-based navigation
Methods that rely primarily on first-person observations at test time and predict actions online.

See: [papers/egocentric_policy.md](papers/egocentric_policy.md)

### 3. Hybrid planning frameworks
Methods that use VLMs for high-level grounding, subgoal generation, or semantic reasoning, while downstream planning/control handles execution.

See: [papers/hybrid.md](papers/hybrid.md)

### 4. Scene-graph-based navigation
Methods that use scene graphs or structured semantic spatial representations for navigation.

See: [papers/scene_graph.md](papers/scene_graph.md)
