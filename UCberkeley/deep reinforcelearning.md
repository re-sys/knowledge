## lecture1:introduction and task overview
- we will learn 
	1. From supervised to decision making 
	2. Model-free algorithm: Q-learning policy gradient actor-critic
	3. Model-based algorithm: planning, sequence model
	4. Exploration
	5. Offline reinforcement learning
	6. Inverse reinforcement learning
- what is reinforcement learning
	- approach for learning decision from experience
- different from other learning
	- supervised: i.i.d data
	- reinforcement learning: not i.i.d previous output influence future input
		- ground truth answer not known, only know if we succeeded or failed
	- some example:
		- dog train
			- action: muscle contractions
			- observation: sight smell
			- Rewards: food
		- robot:
			- actions: motor current or torque
			- Observation: camera image
			- Reward: task success measure
		- inventory:
			- actions: what to purchase
			- Observation: inventory levels
			- Rewards: profit
- why reinforcement learning
	- it can used in language model, image generation
	- can discover new solutions: alpha go and image generation
- what does that leave us
	- data driven AI
		- learns about the real world from data
		- doesn't try to do better than data
	- All about optimization
		- optimizes a goal with emergent behavior
		- but need to figure out how to use at scale
	- so we need data with optimization so that we can do better
		- no optimization no new way
		- no data can not go to the real world
- why machine learning
	- it can help produce complex and adaptable decision
- what should learn
	- end-to-end deep network with RL
	- reward is not the only things matter decision making
	- learn reward from example(inverse reinforcement learning)
		- other is imitation learning
		- this is inferring intentions learning
	- transfer knowledge between domains
	- learning to predict and using prediction to act
		- knowing motion after command motor is important
- leveraging advanced of pretrained model
	- tune a little pretrained model can deploy to other senario
- what challenges still remain
	- 