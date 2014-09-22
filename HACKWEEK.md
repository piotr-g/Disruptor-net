Hey guys, this is the plan for now:

1. Get the disruptor to work - currently project doesn’t build

2. Learn use cases and get some intuition about how to use the disruptor - 
   perhaps by looking into LMAX’s performance tests

3. Find something in our platform for which disruptor is a fit (valuations?)

4. Move that piece of code to disruptor - 
   after understanding how that code translates to the disruptor model

5. Check for correctness of the results produced using the disruptor model - 
   by comparing with our systems results)

6. Compare performance to our system



Subtasks to be handled later (?):

-Retrieve market rates (e.g. fx rates for the previous day), 
so they’re ready for disruptor to load in memory and consume
