# wumpus-prolog

## How to run
1. Download and install SWI-Prolog from [here](https://www.swi-prolog.org/Download.html).
2. Start SWI-Prolog in project directory: `$ swipl`
3. Load the world simulator: `?- [wumpus_world].`
4. Load the agent: `?- [my_agent].`
5. Run the agent: `?- evaluate_agent(1, Score, Time).`
6. Press `y`

Or run this directly: `?- [wumpus_world]. [my_agent]. evaluate_agent(1, Score, Time). y`
