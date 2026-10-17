# Contributing

Contributions that make the search algorithms easier to understand, run, or verify are welcome.

## Propose a change

1. For a bug, describe the input, expected result, actual result, and the Python version you used in an issue.
2. Create a branch for one focused change. If you do not have write access, fork the repository first.
3. Keep examples small and explain any new algorithm's assumptions, inputs, and outputs.
4. Open a pull request describing the problem, your change, and how you checked it.

## Check algorithm changes

Before submitting a change, run the affected example and record the command and result in your pull request. Where applicable, check:

- A goal that can be reached, including the returned path and cost.
- A goal that cannot be reached, so failure is handled clearly.
- A start node that is already the goal.
- Graphs with cycles, so repeated states do not cause an infinite loop.
- For heuristic search, the assumptions required for any optimality claim.

If the change introduces dependencies or changes how an example runs, update the relevant instructions. Do not commit credentials, personal data, or generated environment folders.

## Documentation changes

Check that repository links point to real paths and that Markdown code blocks are closed. Include a runnable command when documenting how to execute an example.
