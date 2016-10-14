# AIR(Aritficial Intellgencne Research paper)

## Table of Contents
- [AIR (Aritficial Intellgencne Research paper)](#Aritficial intellegence research paper)
    - [Active Searches](#Active_searches)
        - [Active object search](#Active_object_search)
        - [LKP Manipulation based guided search](#LKP_Manipulation_based_guided_search)
    - [Bayes and ML](#Bayes and ML)
        - [Bayesian_decision_theory](#Bayesian_decision_theory)
        - [Chap9-Bayesian-Mapping_howie](#Chap9-Bayesian-Mapping_howie)
        - [Deconvolution](#Deconvolution)
        - [L2 for IP](#L2 for IP)



## <a name="Active_searches"></a> Active searches
### <a name=""></a>  Active object search ( [**link to file**](Active Searches/active object search.pdf) )

In this paper, we study the problem of active visual search (AVS) in large, unknown, or partially known environments.
We argue that by making use of uncertain semantics of the envi- ronment, a robot tasked with finding an object can devise
efficient search strategies that can locate everyday objects at the scale of an entire building floor, which is previously
unknown to the robot. To realize this, we present a probabilistic model of the search en- vironment, which allows for
prioritizing the search effort to those parts of the environment that are most promising for a specific object type. Further,
we describe a method for reasoning about the unexplored part of the environment for goal-directed exploration with
the purpose of object search. We demonstrate the validity of our approach by comparing it with two other search systems
in terms of search trajectory length and time. First, we implement a greedy coverage-based search strategy that is found
in previous work. Second, we let human participants search for objects as an alternative comparison for our method.
Our results show that AVS strategies that exploit uncertain semantics of the environment are a very promising idea,
and our method pushes the state-of-the-art forward in AVS.

### <a name="LKP_Manipulation_based_guided_search"></a> LKP Manipulation based guided search ( [**link to file**](Active Searches/LKP_Manipulation_based_guided_search.pdf) )

Object search is an integral part of daily life, and in the quest for competent mobile manipulation robots it is an unavoidable problem. Previous approaches focus on cases where objects are in unknown rooms but lying out in the open, which transforms object search into active visual search. However,in real life, objects may be in the back of cupboards occluded by other objects, instead of conveniently on a table by themselves. Extending search to occluded objects requires a more precise model and tighter integration with manipulation. We present a novel generative model for representing container contents by using object co-occurrence information and spatial constraints. Given a target object, a planner uses the model to guide an agent to explore containers where the target is likely, potentially needing to move occluding objects to enable further perception. We demonstrate the model on simulated domains and a detailed simulation involving a PR2 robot.

People will be adding the abstract of the research papers so that you can directly access the research paper of your interest.
