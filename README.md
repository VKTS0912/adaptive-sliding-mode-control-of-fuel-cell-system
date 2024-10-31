# Fuel cell system
Proton exchange membrane fuel cells (PEMFCs) are the most promising fuel cell technology because of their high-power density, low operating temperature, quick startup capability, and low weight. Efficient use of the PEMFC requires keeping it working at an adequate power point and protecting fuel cells from damage problems. Through this project, we learn how to extract the maximum power from the PEMFC system and protect it from membrane damage by stabilizing the hydrogen and oxygen partial pressure.
## Adaptive Sliding Mode Control of a Fuel Cell System
PEMFC system control has to consider problems related to harvesting electrical energy from the PEMFC stack. Fuel cells have a nonlinear voltage–current characteristic, and the power has several local maximum power points in the I–P characteristic under various operating conditions. Therefore, an MPPT algorithm must be established to improve and optimize the PEMFC system efficiency.  

This project focuses on developing an ``Adaptive Sliding Mode Control`` (ASMC) strategy for fuel cell systems, aimed at addressing the inherent challenges posed by their nonlinear and dynamic characteristics. Sliding Mode Control (SMC) is a robust control approach well-suited for such nonlinear systems, as it ensures stability and precise tracking despite disturbances or uncertainties. By integrating adaptive mechanisms into the SMC framework, the ASMC method dynamically adjusts control parameters, enabling the system to respond more effectively to fluctuations and maintain optimal performance.

Through this project, we managed to model and draw the characteristic curve of the fuel cell. Moreover, a sliding mode controller for the PEMFC system has been designed, successfully extracting the maximum power of the fuel cell.        
### Operation
To see the characteristic curves of the fuel cell, run the ``fuel_cell_characteristic.slx`` file to save the data values, then run the 'characteristic_plot.m' to plot the graph.        
The design and simulation of obtaining the fuel cell's maximum power are shown in ``smc_controller.slx`` file.   
