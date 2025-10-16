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

### Vid-5: Router
- **Learnings:** Learnt how router works: takes a decision to return tool call or just return a normal message on the basis of our input, saw the visual demonstration of the router in the langgraph UI as well.
- **Changes:** changed the function called by tool
- **My code:** https://github.com/indraneel2110/indraneel-langgraph-MAT496/blob/main/router.ipynb

### Vid-6: Agent
- **Learnings:** Learnt how agent works: basically works as an extension of router, where we feed the output after tool is called back to the machine instead of going to the end, and let it decide again whether to call the tool or not. We basically form a loop until the machine decides to not call the tool and go to the end. Also did the tracing on langchain.
- **Changes:** did boolean functions instead of the integer function called by the tool
- **My code:** https://github.com/indraneel2110/indraneel-langgraph-MAT496/blob/main/agent.ipynb

### Vid-7: Agent Memory
- **Learnings:** We built on from the previous video: learnt how agent memory works: basically instead of giving the input together what we want is to take the output and without specifically calling it out, we refer to it and perform another function. We do so by adding checkpoints and calling the reference of the output at that checkpoint when we want to call the tool on the output on a different run.
- **Changes:** did boolean functions instead of the integer function called by the tool and added another code cell to check if memory is really taken from the first tool output or the most recent one, sure enough it's the most recent one
- **My code:** https://github.com/indraneel2110/indraneel-langgraph-MAT496/blob/main/agent-memory.ipynb
