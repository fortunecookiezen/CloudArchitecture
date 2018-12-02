# CloudArchitecture

# Principles
*“The essential thing is action.  Action has three stages: the decision born of thought, the order or preparation for execution, and the execution itself.  All three stages are governed by the will.  The will is rooted in character, and for the man of action character is of more critical importance than intellect.  Intellect without will is worthless, will without intellect is dangerous.”* – Sun Tzu, as quoted in the Marine Corps Warfighting Doctrine

1. Keep teams out of each other's resources
2. Always use the simplest architecture available
3. Optimize first for value delivery, then optimize for cost
*  Develop the solution and monitor it for business value, once it's value has been determined, optimize it for cost. If you cannot determine it's business value, then interate through the process.
## Principles on the selection of tools:
1. Always start with the tools you have
*   Pick tools that are available to you *now* and start there. Use that to develop the use cases and business values for what you are trying to accomplish. Good enough is often better than best. I'm going to call this metric *"Mean Time To Value (MTTV)"*

    You achieve low MTTV by asking yourself the following questions. When you get to the first *yes* answer, stop there and do that.

*   Is it available in AWS or Azure?
*   Is it available in the open source community?
*   Is it available from a 3rd party?
*   Can I build it myself?

    Here's an example of that thought process in action:

![Buy it or Build it?](https://s3.amazonaws.com/fortunecookiezen/github/images/tool_decision_tree-3.png)
