# Single Photon Detection

### Description of Laboratory IV Module:

Photon Detection: This is one of the most important enabling technologies for quantum science and recent breakthroughs for what are called superconducting nanowire single photon detectors (SNSPD) mean that these not only have near perfect detection capabilities but also have photon number resolving (PNR) capabilities – they can distinguish how many photons are in a pulse, which is another extremely important step for many quantum photonic systems in quantum communication and computing. Here we want to work on improving this PNR capability, for example by sampling the detection signals. We are looking at multiple approaches from training neural networks on this tasks, to utilising next generation FPGAs to sample signals in real-time.  It will involve cryogenic systems, optics, electronics, FPGA and neural net programming.

### Description of the Code

I was iniatially tasked to write a code that was able to read the .h5 files from the oscilloscope and be able to plot all the data files inside each .h5 file. Then getting the maximum amplitude of each plot and creating a histogram to see if there were any discernible pattern to identify single, to two, to multi photon events.

