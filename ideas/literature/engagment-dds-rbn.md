#literature engagement past december 2025 into new year 2026 during topic direction shift
#discrete dynamical systems and autonomic computing 

this document records my thoughts and understadnings of the key literature on autonomics as i find and engage with them. notebaby for this section is around on particular eyeopening paper toward DDS and RBNs

## context for reading 

intial project attempts focused on implementation driven security mechansims (moving target defence and autonomic endpoint security))
after encountering feasibility and validation issues when wokring wiht closed apple systems i returned to foundational research on autonomics going back to my many lists of sources made over five years since my orignal EPQ in college
i have not thoroughly read through all of my list and was reading around ieee's section in my list after foucsing most of my literature reviewing on more recent publications. when in reality most of the talk around autonomics is around the 2000's after IBMs model proposal of autonomics itself.  

key sources for this sittings readings: 
## IEEE 1571119
## Meta dynamic states for self healing autonomic computing systems

IEEE 5395120
Autonomic Computing Paradigm to Support System's Development

IEEE 5406605
A survey on autonomic computing research

## thoughts around meta dynamic states for self healing autonomic computing systems< 
i selected this paper as a part of my investigation of the self healing section of autonomics orginally intending for it work around my adaptive security mechanism. 
however this work reframed my focus of my project by showing how homestasis and recovery can emerge through ver low level system dynamics rather than being explicity programmed. whihc was my orignal issue this my topic and its need for a product. 

before making thorough notes about this paper the claim that a higher order autonomic behaviour can emerge for free from the natural organisation of a systems state space. 

the authors used a disscrete dynamical system as the autonomics and how to analyze behavior through the state space. giving me a idea of how to theorically involve self healing in a system. 
the authors actually foudn this through acknowlegding the 'natural' behaviour that gave autonomics its name through the human nervous system and refered to this use of DDS like the biological process of homeostatis. 
making a great find for the true rules of autonomics and making a place to quote my own papers of autonomics in my final project. 

the statement of 

all complex systems naturally organise their state space into attractors and basins of attraction, and this organisation can be eploited to achieve self-healing and robustness. 

and from this it says a system much like the human body will react to faults with predefined rules and the system will track where it is in the state space. 
recognises when it was entered a unwanted spot and actively steers itself back toward a wanted state. 
just like homeostatis

a major contribution of the paper is the concept of meta dynamic states. 

instead of tracking indivdual microstates the system tracks the attractors, basins of the attractors and transient regions

each MDS represents a higher level descripton of system behaviour not a snapshot state. 

this would allow a system to remain dynanically invariant DSI 
as the microstate may change but the systems behavioural outcome reamins predicatable. 

the abstraction is crucial for scalability and self-awareness. 

on the note os selfawareness the awareness in the models is structral 

the system becomes aware when a perturbation moves into an unknown or undesirable MDS
and recognises that it not longer belongs to a safe attractor basin. 

which is important because not all perturbations are danggerous to the system, some of the disturbances will be from natural decay back into stable attractors.
these distinctions prevetn unnecassary corrective actions and safe the cost to run them.

the action iself of self heling through mircostate control, 
once awareness is triggered the system plans recovery by idenfitifying possible mircostate changes and evaluatiing theri costs (where y addition of kruskal would be)
and selection paths that return it to a wanted state. 

microstate MDS graph and self healing graph from the paper formalise this process. 
in these graphs i found its important that the recovery isnt brute force or a large process, and that the intervention is minimal and tagerted. all things you would want on a system for users qaulity of usage and the systems cost. 
before the costs for anything acting as aware was large and not scalable to smaller systesm likes laptops or user devices. 
in these models too is the cost and time contstraints shown explicitly. 
all of which align wiht real world system contraints.
so despte being theorical it can be applied. 

from before reading this specific paper most writing was was rule based adapatation and externa;; impossssed logic control. 
but this paper showed me recovery mechansims can be emergent and system safety can be framed wiht movement in a state space. 
and failures to the security can be interpreted as transitions into unsafe aatractors that can be back tracked and traced. 

these ideas mean that there was a new possiblity to show a theroical near solution to when intrusion, faults and degradtion being treated like dynamical perturbation 
and defence is a state space reorinetation rather than a reaction that was large and would halt other processes of autonomic behaviour.

this of course is still to be referenced to my topic nd my topic needs to be in relation to cyber security. as my initial ideas five years ago to use autonomics to extend the time before human intervent
is needed for system, network of personal device cyber attacks. 

but after reading through this paper it gives me a theorical foundation for self healing systems and a language to descript resilince formally and a framewokr i can presonally adapt rather than directly implement. 

--------

IEEE 5395120
Autonomic Computing Paradigm to Support System's Development


