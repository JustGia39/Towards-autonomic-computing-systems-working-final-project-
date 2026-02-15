simulation and raw logic ideas and references, 
having been working no since last enrry; 

put into the3 literatre review since this is the first and main paper that started it all whihc is the foundational autonomic computing vision 
by kepart and chess. 
though this was orginally founded for a solution to the comp;exity problem it is a solution for many more problems and advances in computing 

another of the main papers that centeral to the founding of autonomics and its design is the MAPE-K control loop
the IBM blueprint which will act as my foundation for the algorithmic backing of my paper. 

the MAPE-K stands for: 
Monitor 
Analyze 
Plan 
Execute 
(knowledge) 

i will be at its simpliest form trying to model a autonomic manager algorithm 
so it becomes wiht my uses of other logic from mentioned papers in the literature review section: 

state - monitor - analyze - choose attrator - transition 

this is because it makes it more mathematically exepressible for my execution. 

i am leaning this algorithmn to not need ai or have full autonomy as exepcted and explicititly outlined. 

despite the main four properities i am not strictly tied to all of them as they are not arbitrary
i will be strucutring each section to my ability and reframing when reacted to not over shot my capabilities and this papers reach. 

intents and current needs for each of the four componentes 

self healing system: 
##current foundations of algorithmic direction:

anomaly detection model 
watchdig process 
redundancy checks
rollback mechanishms 
predicitve failure modelling 

##production direction: 

tracks system proformance metrics, identifies deviation from the baseline 
and classifies severity of deviation and triggers corrective action autonatically 
which look like: 
restarting failed processes, 
reallocating resources 
reverting to a stable configration

Optimization

##current foundations of algorithmic direction: 

heuristic optimation 
reinforcement style adaption 
resource allocation slgorithms 
load balancing stratgies

##production direction: 

an adaptove scheduler that acts on usae patterns, peak load behavior and computational bottlenecks. 
to dynamically redistribute tasks. 

Configuration

##current foundations of algorithmic direction: 

self-strcuturinh 
environment aware 
parameter adjustment

##production direction: 

rule based configs
context sensitiv intialization 
automated dependency validation

self defence 

##current foundations of algorithmic direction: 

anomaly based intrustion detection 
behavioral profiling 
rate limited logic 
automated containment 

##production direction: 

detecting unusual activity 
isolating affected modules 
logging data for forensics 
maintaining core system function. 


for the sake of my ability this modules may act independentaly in their demos but should exist all functioning TOGETHER as autonomics needs. 




-------------
