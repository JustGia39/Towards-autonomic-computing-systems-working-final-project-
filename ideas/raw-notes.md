#raw research notes 
this document contains the unfiltered researcg notes, brainstroming entries and exploratory ideas recorded throughout the early and middle stages of the project 

entries are preserved largely as originally written to document the evolution of the research directions. 
a note to these notes are wildly unorganised and often missing there timestamps, having been worked at continuesly but at random intervals from my laptops notebook

-------------------

Final project ideas 

Monday 22nd September -1:16pm 
(In costa cause no wifi in my house)

Remake autospy for Mac OS 

Do my autonomic security system to defend Mac 

Look in SOC- 
Autonomic security operations 
To relate both my junior thesis’s and potential future research position for PhD

This idea covers both the research driven and problem solving categories 

Whereas the autopsy remake is just solving the problem of not having good security tools available for Macs 


With the SOC I can relate back to my already researched sources and contacts for the research. 
But needs more in the security aspects and the actual implemation of it 

Problem is its likely not answerable in my timeframe


Cannot rely on the remake of Mac autposy- cause application making is not accepted


The goal of whatever im aiming for is to extend the time before a a system will require human intervention in security aspects. 
When a system is under threat I want to make something to counter it for just enough time to protect assets till human intervention is able. 

It would good for all types of digital assets - most notably banks or systems that require on call software engineers. 
This also is heavily prevalent in cloud-based tech. 
-
Maybe link in cloud asset protection. 

To simplify this idea in case it is too big or not accepted- 
Added security measures to a personal Mac OS system and or a Mac/cloud based network. 

Thus far ideas persist of: 
* Security measure to protect assets/personal data 

* To delay human intervention to aid on-call engineers/developers or tech wont front facing code. 

* Autonomics-cloud-based-personal systems 

*       Usable to Mac OS 


The reason I wish to include autonomics outside of pure and continuous interest is the fact that it defends a system itself using its autonomic properties.
Self healing, self optimisation, self configuration (the most important for the sake of security.) and self defence. 

Self healing: 

Self optimisation:

Self configuration: 

Self defence: 

I am NOT looking to make this an autonomous system but an autonomic on

Monday lecture- 29th September journal log 9:05

From physical notes taken at lunch: 
Creating a more specific niche in topic. 
Focus shift with keeping main concepts and implementation. Find something more feasible. 
 

——————

Notes from 29th to 10th of october from notebook- 

Autonomic acting firewall? 

Autonomic acting elements for adaptive network structure for protecting system. 

Goal for project- 
Pre-attack prevention 
After/during attack defence 

Pre-attak / checking state and monitoring network/ system 

Anctipate Attack 

Defense during attack/ mitigation during attack 

Use of autonomic elements in defence of a (network, assets, personal system, device)

Focus on network and personal systems with implied protected assets. 

Have to monitor computer/network state and adapt to it via autonomics

Try and make focused around Macs/apple systems/ networks as they are heavily in sync in network (ie apple environment where all devices are connected) 

Project names? 
Adapting autonomic elements toward cyber defence of a (network, Mac network . Personal system)

Development of autonomic element word network security\\

Problems: 
Feasibility, 
How to test literally everything with limits like only apple devices (ie Mac laptop, iPad and phone outside of uni)
Need a router? 
Timescale 
Difficulty of project in a whole 
Focus more on research 

The perfect network (for security)

Could you transfer data on a network to different servers when a server is under attack? 
Make a network that acts like the human body in defence- like autonomics. 

Shifting servers routinely at random to avoid attacks. 

With an adaptive firewall / VPNs 
Active changing Mac address to avoid sniffing or scanning 





———————————

Final brainstormed project ideas- 

Autonomic Endpoint Defence for macOS: Adaptive Isolation & Mitigation 

What it mainly answers: can autonomic defence mechanisms on MacOS meaningfully extend the response time window and reduce system damages during a live cyber-attack. 

A prototype security agent for macOS that detects early signs of compromise and automatically performs safe, reversible actions (inabling firewall rules, temporary isolation and process blocking) to slow or contain an attack until human intervention is available. 


Self-Configuring Mac Defender: An Autonomic Layer to Delay Human Intervention

What It mainly answers : How effectively can autonomic self-configuration improve a systems security posture and reduce reliance on manual intervention

A self configuring security prototype that adjusts its own settings and defences in real time (with network rules, system permissions and resource limits) in response to changing threats or performance conditions. 


Autonomic Elements for Network Resilience: A Moving-Target Approach for Apple Environments

What it mainly answers: Can autonomic moving target techniques measurably increase the resilience of apple-based personal networks against scanning or targeted attacks. 

A research focused prototype exploring how autonomic elements (like dynamite,ic IP , MAC or route changes) can make apple-based networks more resilient to attack using a moving target defence principles. 

Mini-SOC for macOS: An Autonomic Agent that Detects, Adapts and Contains
Autonomic Acting Firewall: Adaptive PF Rules and Moving-Target Techniques for Personal Systems and networks

What it mainly answers: Can autonomic SOC-sytle agent improve detection and immediate containment on macOS endpoints without human input. 

A lightweight mini Security Operation Centre prototype for MacOS that monitors system activity, autonomically reacts to suspicious behaviour, and logs actions for later human review- bridging detection and response on a single endpoint. 


———————



Add notes from ideas in pen testing lecture- 

Cross-site sql attack defence 

Memory corruption attacks- prevention and defence 

Have an isolated testing environment that runs checks on connections to the network which after passed checks - connects to the official network 
Have an attack ready environment 

And maybe - at attacks back to seen attacks by dos ing them when something try to attack the network-

Is this even legal? Apparently not? 
Would it hurt an innocent third party? Entrapment?


A hack-back scenario 
It has to be resonable to the attack under the requirement of self defence 
(Philisocial idea) 
Is hack back self defence allowed like physical self defence 
So having the attack is an inevitable and needed process of cyber security. 


Maybe have a system ‘passout’ to prevent further issues or corruption 


What I want Is a moving network with many prevention techniques applicable to networks and personal system networks 


Aim to prevent long recovery times and extent human intervention toward an attack 

Wednsay 29th of October - 
Final project topic finally picked as 
Finished off the proposal and send it in and maybe tweek concept. 
And start on the literature review. 


How to protect from mass server attack 

16 servers

8 for data storing 
8 for ai and monitoring 
2 sandbox servers 
Added firewalls 


New development as of the 5th of January, attempts toward original proposal not within capabilities. 
Return to a more abstract topic about possiblilties of algorithms toward autonomics key principles 

Problems found with current topic- 
Working with apple systems could be tricky to validate as apple systems are closed. 

The promise of moving target defence implies a  made and implemented security system which is not possible with my capabilities. And promising autonomy in the system when that is not yet a system that exists. 

To move froward I intend to focus on modelling how autonomics could emerge using formal systems and algorithms to model near autonomic behaviour 

New working title: 
Towards autonomic computing systems: 

A Discrete Dynamical Systems Approach to Self-Managing Behaviours

Modelling Self-Healing, Self-Optimising and Self-Protecting Behaviour in Autonomic Computing Systems

Mapping out my needs for this title and work are proposed through: 
A state transition problem 
Governed by he local rules of autonomics 
And producing a global behaviour macro state 

Autonomic Property	RBN Interpretation
Self-configuration	Nodes adapt connectivity (k)
Self-healing	State transitions recover from perturbations
Self-optimisation	Attractor basins with minimal cost
Self-protection	Avoidance of unstable / malicious attractors

(Reference from paper)

My addition is to add a learned topic like kruskals algorithm / the other one to find the most effeicnet attractors with the cost efficiencies in mind. 

As an attractor landscapes can be displayed in state transition graphs
In the graphs are costs like energy (reference back to my advanced networks module) instability and record time. 

And kruskals algorithm is used to identify minimal spanning structures 
Reduce exploration cost of the state space 
And approximate efficient attractor basins 


