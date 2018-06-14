To make the file work properly, you'll need to first download the
FrozenLakeEnv from:

https://github.com/openai/gym/blob/master/gym/envs/toy_text/frozen_lake.py

Then add the following to the MDP with agent:

#obtain the one-step dynamics for dynamic programming setting
self.P = P
