This is an agent based prey and predator model where each agent has a little brain, represented as a Neural Network. The Neural Network evolves via a genetic algorithm.
However, here, I implement cooperation!

There are many parameters to play with, which, will be optimized soon!

-------------------------------
COMING SOON 
-------------------------------
- Optimized parameters for great visualizations!
- Better visualization of the agents.
- Optimized code for faster runtime.
- CUDA integration?
- Real time population display.

------------------------------
FUNCTIONAL THINGS
------------------------------
In order to run and build the script, please ensure you have zig installed, and run the following command in your zig environment / directory.

$ zig build run -Dcpu=<your_cpu_architecture_here> -Doptimize=ReleaseFast

Note, that if you do not know your cpu architecture, you can just delete the -flag (I personally use a tigerlake).

![Model](https://github.com/mengsig/CooperativePredatorVsPrey/blob/main/picture.png)

Please enjoy, and share!

By: Marcus Engsig
