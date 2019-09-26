# Why Self-Reconfigurable Modular Robots? Why ML?
During High School, I was fascinated by the fictional-yet-also-based-on-real-life technology shown by the movie "Big Hero 6", especially the microbots.
However, the technology that the movie based it on has stopped posting records of research, perhaps due to losing worth of investment within current technology, or it required a technological breakthrough to have a more realistic view of its goal.

I then thought: can Machine Learning be a technological breakthrough?

Of course, there are probably still more breakthroughs required in other fields such as hardware, but I was curious to see if Machine Learning could contribute something to this technology.

I then thought of creating a physical simulation within the Unity 3D engine.
I also found out that Unity had Machine Learning Agent Beta kits.

I had to try it out.

## Physical Simulation
I simulated electromagnetic forces with actual physical equations and Unity's force vectors.

I also modeled the individual modular units, and implemented Prefabs to make use of the simulated electromagnets.

Making this simulation was overall a good learning experience for me to become comfortable using Unity.

## Testing
I tested the Machine Learning Kit using different reward values for different functions of the modular robot, in order to find the most effective reward value for the modular units to form given shapes.
The testing process was to have the unit swarm form 4 different basic shapes, and measure the time it took to assemble.

Below is record I kept track of for different reward values.
https://docs.google.com/spreadsheets/d/1MSqbnS0RPPwDxcafFDZocpPQ8EvCys4iReD2WnIKkLg/edit?usp=sharing

## Conclusion
Although this is obviously not a practical solution that can be used immediately for self-reconfigurable modular robots, it was a good learning experience to understand the potential of machine learning and its viability for this purpose.

Below is the Official README from Unity's ML-Agents Documentation

# Unity ML-Agents Documentation

## Getting Started
 * [ML-Agents Overview](ML-Agents-Overview.md)
    * [Background: Unity](Background-Unity.md)
    * [Background: Machine Learning](Background-Machine-Learning.md)
    * [Background: TensorFlow](Background-TensorFlow.md)
 * [Installation & Set-up](Installation.md)
    * [Background: Jupyter Notebooks](Background-Jupyter.md)
    * [Docker Set-up](Using-Docker.md)
 * [Getting Started with the 3D Balance Ball Environment](Getting-Started-with-Balance-Ball.md)
 * [Example Environments](Learning-Environment-Examples.md)

## Creating Learning Environments
 * [Making a New Learning Environment](Learning-Environment-Create-New.md)
 * [Designing a Learning Environment](Learning-Environment-Design.md)
     * [Agents](Learning-Environment-Design-Agents.md)
     * [Academy](Learning-Environment-Design-Academy.md)
     * [Brains](Learning-Environment-Design-Brains.md): [Player](Learning-Environment-Design-Player-Brains.md), [Heuristic](Learning-Environment-Design-Heuristic-Brains.md), [Internal & External](Learning-Environment-Design-External-Internal-Brains.md)
 * [Learning Environment Best Practices](Learning-Environment-Best-Practices.md)
 * [Using the Monitor](Feature-Monitor.md)
 * [TensorFlowSharp in Unity (Experimental)](Using-TensorFlow-Sharp-in-Unity.md)
 
## Training
 * [Training ML-Agents](Training-ML-Agents.md)
 * [Training with Proximal Policy Optimization](Training-PPO.md)
 * [Training with Curriculum Learning](Training-Curriculum-Learning.md)
 * [Training with Imitation Learning](Training-Imitation-Learning.md)
 * [Training with LSTM](Feature-Memory.md)
 * [Training on the Cloud with Amazon Web Services](Training-on-Amazon-Web-Service.md)
 * [Using TensorBoard to Observe Training](Using-Tensorboard.md)

## Help
 * [Migrating to ML-Agents v0.3](Migrating-v0.3.md)
 * [ML-Agents Glossary](Glossary.md)
 * [Limitations & Common Issues](Limitations-and-Common-Issues.md)
 
## API Docs
 * [API Reference](API-Reference.md)
 * [How to use the Python API](Python-API.md)
