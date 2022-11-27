# LabExercise2
NS2 simulations to simulate flow transfer in networks
Prompt: In the first task you will compare the analytical average flow transfer times provided by the 
equations in (9) to the corresponding simulated transfer times. The artificial loss-module in ns2 generates losses randomly in the bottleneck link 
queue so that each packet entering the queue is dropped with an equal probability p (an example of 
introducing a loss module can be found in section A.5, in the appendix) 
Use four different RTT classes and set the inter-arrival times of the TCP-flows in each class so that 
the theoretical offered load in the bottleneck link at the flow level equals 0.8. This ensures that the 
network will not be in a pathological congestion situation. The task is then to compare the results of 
the theoretical model to simulated results with different values of the packet loss probability p. In 
more detail measure and compare the following: 
• Using data from the simulation, give estimates for the mean file transfer times and 
throughputs of each class based on applying Eq. (11). 
• Include also confidence intervals in your results. 
• Plot your results in a graph as a function of p. 
• Assume that RTTs for each class consists of only the propagation delays when applying the 
DPS model to TCP. Compare the simulated mean delays and throughputs to the theoretical 
mean delays and throughputs given by Eq. (9). What can you conclude? 
• Compare also the ratios of the performance, i.e., compute Wk/W1, k = 1,…,4, for simulations 
and for the theoretical model. What can you conclude as p is varied?


TASK 2: 
In this task you will perform the same simulations as in task1 but in a larger topology. Now, you 
will not add any artificial losses but assign a finite limit for all the buffers, allowing the losses to 
occur naturally. Since the analytical results of (9) are only valid for a single-bottleneck case, in 
task2 no analytical results are required. You should consider, how the larger topology and “real” 
Loss Module queuing behaviour changes the flow transfer times of different RTT classes compared with the more 
controlled setup in task1. You should modify the load level in the bottleneck link in each iteration 
step by step and observe what happens to the flow transfer times and flow throughputs of different 
RTT classes and to their relations. In more detail, you are expected to: 
• Using data from the simulation, give estimates for the mean file transfer times and 
throughputs of each class based on applying Eq. (11). 
• Include also confidence intervals in your results. 
• Plot your results in a graph as a function of the load. 
• Comment the behaviour of the system as a function of the load. Compare also the ratios of 
the performance, i.e., compute Wk/W1, k = 1,…,4, for different values of the offered load. 
What can you conclude from these?
