# LangGraph – Subgraphs and Composition

To learn **Subgraphs and Composition**, create separate Python examples for each concept. This lets you practice each feature independently and understand how smaller workflows can be combined into larger ones.

## 1. Subgraphs – Types of Examples

A **subgraph** is a LangGraph workflow used inside another LangGraph workflow.

| No. | Topic | What you will learn | Example |
|---:|---|---|---|
| 1 | Basic Subgraph | Create a graph and use it inside another graph | Parent graph → Child graph |
| 2 | Shared State Subgraph | Parent and child use the same state schema | Shared `TypedDict` |
| 3 | Different State Subgraph | Parent and child use different state schemas | Input/output mapping |
| 4 | Nested Subgraphs | Use a subgraph inside another subgraph | Parent → Child → Grandchild |
| 5 | Multiple Subgraphs | Execute multiple subgraphs in parallel | Research + Analysis |
| 6 | Conditional Subgraphs | Select a subgraph based on conditions | Support vs. Sales |
| 7 | Subgraph with Reducer | Merge updates from subgraphs | Multiple results |
| 8 | Subgraph with Memory | Maintain state across subgraph executions | Conversation history |
| 9 | Subgraph with Human-in-the-Loop | Pause and resume a subgraph | Approval workflow |
| 10 | Reusable Subgraphs | Reuse the same compiled subgraph in different workflows | Shared validation workflow |

## 2. Composition – Types of Examples

**Composition** means combining smaller nodes and graphs to build larger workflows.

| No. | Topic | What you will learn | Example |
|---:|---|---|---|
| 1 | Sequential Composition | Connect nodes one after another | A → B → C |
| 2 | Parallel Composition | Execute multiple nodes together | A + B + C |
| 3 | Conditional Composition | Select different workflows | If/Else |
| 4 | Branching and Merging | Split and combine workflows | Fan-out → Fan-in |
| 5 | Graph Composition | Combine multiple compiled graphs | Graph A → Graph B |
| 6 | Dynamic Composition | Create branches dynamically | Process multiple documents |
| 7 | Map-Reduce Composition | Process multiple inputs and combine results | Multiple document summaries |
| 8 | Hierarchical Composition | Build workflows using nested graphs | Main → Department → Task |
| 9 | Reusable Components | Create reusable workflow components | Authentication + Validation |
| 10 | Error Handling Composition | Combine workflows with retry and fallback | API → Retry → Fallback |

## 3. Recommended Folder Structure

Create a separate file for each example so you can practice independently.

```text
langgraph-learning/
│
├── 01-subgraphs/
│   ├── 01_basic_subgraph.py
│   ├── 02_shared_state_subgraph.py
│   ├── 03_different_state_subgraph.py
│   ├── 04_nested_subgraphs.py
│   ├── 05_multiple_subgraphs_parallel.py
│   ├── 06_conditional_subgraphs.py
│   ├── 07_subgraph_with_reducer.py
│   ├── 08_subgraph_memory.py
│   ├── 09_subgraph_human_approval.py
│   └── 10_reusable_subgraphs.py
│
└── 02-composition/
    ├── 01_sequential_composition.py
    ├── 02_parallel_composition.py
    ├── 03_conditional_composition.py
    ├── 04_branching_merging.py
    ├── 05_graph_composition.py
    ├── 06_dynamic_composition.py
    ├── 07_map_reduce.py
    ├── 08_hierarchical_composition.py
    ├── 09_reusable_components.py
    └── 10_error_handling_composition.py
```

## 4. Suggested Learning Order

1. Complete the 10 subgraph examples in order.
2. Complete the 10 composition examples in order.
3. For each example, write the graph, invoke it with sample input, and inspect the final state.
4. After completing both sections, build one mini-project that combines multiple subgraphs and composition patterns.