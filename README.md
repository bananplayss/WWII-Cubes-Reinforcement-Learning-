# WWII-Cubes-Reinforcement-Learning-
Self-Learning Tactical Agents in a simplified WWII Arena using Multi-Agent Reinforcement Learning  
  
Documenting my work on a planned, two-month project where I delve into an interesting topic: Machine learning, technically reinforcement learning. I will also attempt to make the agents work with each other and create a multi-agent learning environment.  
Day 1-7:  
Started with research. Mainly [understanding ML in general](https://apxml.com/courses/introduction-to-machine-learning), then reading [setting up](https://docs.unity3d.com/Packages/com.unity.ml-agents@4.0/manual/Installation.html) and [learning about the MLAgents Toolkit](https://docs.unity3d.com/Packages/com.unity.ml-agents@4.0/manual/Learning-Environments-Agents.html) from the documentation. I started with understanding the basic concepts like what RL is, what an agent accomplishes, what is an environment, reward types, episodes, etc.  I also dipped my toe into basic neural networks.
Then I tried playing with the [example environments](https://docs.unity3d.com/Packages/com.unity.ml-agents@4.0/manual/Learning-Environment-Examples.html) the package provides and reading the implementations for them.  
Day 7-14
I started experimenting with the toolkit by myself and made an 'aimbot' agent which tracks a target (stationary then moving). The benchmark average reward was almost maximized but there are still things missing, which I don't yet understand. On day 12, I completed the aimbot model and made the AI move itself but it quickly confused itself and started spinning. Initially I gave it observations such as the angle between the forward vector and the target's position, it's rotation, and then mixed in position, which again, confused the agent so I had to remove it. Then I pondered about what the actual functionality will be for the implemented agent (and the upcoming versions), and I came up with two ideas: To comply with the title "Multi-agent" learning, I thought an environment with two commando units (making a team) in a maze against more teams would be a cool idea. But one of my friend said that it was pretty basic, and that my other idea was much better. A chaotic WWII environment with multi-agent learning. Yes, that's it! An exciting idea. So let's get into it in the third week. 

*currently in the making*   
made with Unity 6 using the [mlagents-toolkit](https://github.com/Unity-Technologies/ml-agents)  
w
