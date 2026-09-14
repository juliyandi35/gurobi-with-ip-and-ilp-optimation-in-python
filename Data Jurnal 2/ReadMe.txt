- This Data set is used from different published papers in container/block relocation problems.
- The used instances are further processed to fit the research topic of "The Block Relocation Problem with Appointment Scheduling (BRPAS)". 
- In the BRPAS, we introduce a new optimization problem that studies the container relocation in the container terminal under the appointment scheduling for container pickup operations.
- Since we are introducing a new problem, which is different from the existing work in the literature, we used some data sets from existing published work and modified them to fit our approach. 
- However, the developed instances still can be comparable to the existing original instances. 
- In this data set , the uploaded files are named with authors' names of the original data set. 

------------------------------------------------------------ 

*This Data set includes a subset of instances from the following papers to solve the BRPAS:

1- Silva, M. de M. da, Erdoğan, G., Battarra, M., & Strusevich, V. (2018). The Block Retrieval Problem. European Journal of Operational Research, 265(3), 931–950. https://doi.org/10.1016/j.ejor.2017.08.048

2- Tanaka, S., & Takii, K. (2016). A faster branch-and-bound algorithm for the block relocation problem. IEEE Transactions on Automation Science and Engineering, 13(1), 181–190. https://doi.org/10.1109/TASE.2015.2434417

3- Caserta, M., Schwarze, S., & Voß, S. (2012). A mathematical formulation and complexity considerations for the blocks relocation problem. European Journal of Operational Research, 219(1), 96–104. https://doi.org/10.1016/j.ejor.2011.12.039

----------------------------------------------------------------------------------

* The used instances give the bay configuration and pickup time/order of containers in the bay.

* We used the bay configuration to process the instances ,and we further assumed the BRPAS parameters.

* BRPAS Parameters (as shown in data files):

a= Acceptable shift of container pickup appointment time window. (a=Delta in BRPAS formulation)
b= Maximum Queue length at bay (b=L in BRPAS formulation)
T= Number of time windows
C= Number of stacks
H= Maximum Height of bay.
N= Number of containers in the bay initial configuration.
G= Maximum number of containers moves (retrievals and relocations) per time window.
mu= Maximum number of containers relocations. (only for the BRPAS(flex))
p= preferred pickup time (array)
I = initial bay configuration (array)

