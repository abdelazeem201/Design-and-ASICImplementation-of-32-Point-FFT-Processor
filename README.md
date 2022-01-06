## *Introduction:*
I present a novel pipelined fast Fourier transform (FFT) architecture which is capable of producing the output sequence in normal order. A single-path delay commutator processing element (SDC PE) has been proposed for the first time. It saves a complex adder compared with the typical radix-2 butterfly unit. The new pipelined architecture can be built using the proposed processing element. The proposed architecture can lead to 100% hardware utilization and 50% reduction in the overall number of adders required in the conventional pipelined FFT designs. In order to produce the output sequence in normal order, we also present a bit reverser, which can achieve a 50% reduction in memory usage.

<img src= "https://github.com/abdelazeem201/Design-and-ASICImplementation-of-32-Point-FFT-Processor/blob/main/Pics/design.png">

## *Synthesize:*

I have succeeded synthesis the design and met  my constraints.

## Design Specification
|Spec        | value         |
|----------- | ------------- |
|Cycle time  | (10) ns       |
|Total area  | 202213.12 µm^2|
|Power       | 2.9519 mW mW  |
|Techonlogy  | UMC 130nm     | 

<img src= "https://github.com/abdelazeem201/Design-and-ASICImplementation-of-32-Point-FFT-Processor/blob/main/Pics/FFT.png">
