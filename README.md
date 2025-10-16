# indraneel-langgraph-MAT496
# Name- Indraneel Ghosh
# Roll number- 2410110146

## MODULE 1:


### Vid-1: Motivation
- **Learnings:** Learnt a bit about what langgraph is: a more low level and more controllable framework compared to langchain, what do we want to achieve with it: basically we want to use it to balance the application's reliablity as agent control increases. Also peeked into the future what we'll learn throughout the course.

### Vid-2: Simple Graph
- **Learnings:** Learnt how to deploy basic graph mechanisms like making nodes: starting node, end node and the nodes in between, and using state to decide which node to visit.
- **Changes:** made another node and changed the randomness from 50-50 to 30-30-30 between 3 nodes, changed the prompts
- **My code:** https://github.com/indraneel2110/indraneel-langgraph-MAT496/blob/main/simple-graph.ipynb

### Vid-3: Studio
- **Learnings:** Learnt about what langsmith studio does: basically allows us to visualize the graphs, saw the live demonstration of the decision state between 2 nodes covered in vid 2.
<img width="1919" height="865" alt="image" src="https://github.com/user-attachments/assets/0511df26-225b-4549-ace4-42e2e79a1dd4" />
<img width="1917" height="876" alt="image" src="https://github.com/user-attachments/assets/86c13b6e-9720-43c0-84e8-877b8ba13aea" />

### Vid-4: Chain
- **Learnings:** Learnt how to build a simple chain in langgraph using direct chat messages and indirectly through tool calls that execute a function, learnt how to basically use messages as a graph state.
- **Changes:** tried different prompts and changed the function called by tool
- **My code:** https://github.com/indraneel2110/indraneel-langgraph-MAT496/blob/main/chain.ipynb
