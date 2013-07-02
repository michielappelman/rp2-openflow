RP2 Log
=======

2 june 2013
-----------
 - improved first draft (v0.1) of proposal and sent it to Rudolf

3 june 2013
-----------
 - got feedback from Rudolf
 - changed problem description, proposed solutions, approach, planning, almost everything in the proposal

4 june 2013
-----------
 - prepare for meeting with Rudolf
 - combining MPLS and OpenFlow? compare feature sets
  - research MPLS PWE3: 3985, Eth: 4448, Types: 4446
 - notes on research after meeting with Rudolf (notes-20130604.txt)
 - collected research papers on NFV, Fast Recovery in OpenFlow, Carrier Grade Networks in OpenFlow
 - added Rudolf to a shared Dropbox folder

5 june 2013
-----------
 - collected data on 

6 june 2013
-----------
 - worked on the proposal, hopefully for a final version
 - answered some questions, came up with some hypotheses (see Research Question)
 - analyzed other contemporary protocols and new papers, got pretty lost in that...
 - sent the new version to Rudolf and asked for an appointment on the 7th.

7 june 2013
-----------
 - primarily worked on the taxonomy in the morning and fine-tuning the proposal
 - met with Rudolf, who again had a lot of different ideas, work out notes in 'notes-20130607.txt'
 - again have to rewrite most of the proposal so asked Cees for an extension

8 june 2013
-----------
 - rewrote proposal, sent draft to Rudolf (v0.4)
 - got some preliminary notes, integrated them
 - drew out some of the taxonomy (on old-school paper), relations between protocols/techniques, features. will need to figure out a way to digitalize this
 - unfortunately have been delaying plans the whole day and need to send the draft version (0.5) to Cees at 17:00
 - other changes will need to wait untill tomorrow

10 june 2013
------------
 - changed the research question to reflect Rudolfs suggestion
 - drew out some thoughts on how to implement dynamic VPNs
 - tried to find some other papers with focus on dynamic VPNs, wasn't really succesful: mostly based on research by Rudolf et al.

11 june 2013
------------
 - made a spread sheet with an overview of technlogies fuctions (comparison.numbers)
 - looked up A LOT of details

12 june	2013
------------
 - finished the overview of different technlogies, added a view features/specs
 - added a table with an overview of protocol stack

13 june 2013
------------
 - made a comparison between using MPLS/SPB/TRILL for step-by-step VPN setup and OpenFlow
 - extended the list of the protocol stack and where changes should be made when adding VPNs
 - added simple VLANs as a technology to show the limitations, evolution into PBB and SPB

14 juni 2013
------------
 - to get a grip on the direction I'm moving in, I set up the first report document in LaTeX
 - essentially just pasted the proposal in there, but did make some additions wrt Scope
 - made a start with the State of the Art part, giving an overview of the technologies available

17 june 2013
------------
 - finished the state of the art section, safe for the OpenFlow piece

18 june 2013
------------
 - OpenFlow bit finished, was a bit hard to get into a certain direction without rehashing too much of the introduction. might need more work
 - worked on some designs and flows of information in both MPLS and OpenFlow setup

19 june 2013
------------
 - was feeling a bit under the weather (and the forecast for the actual weather was terrible) so I worked from home
 - got some ideas on paper, but not much...

20 june 2013
------------
 - expanded on the workflow of the two types of provisioning
 - looked at the Access-layer problem: limited switches there mostly (no MPLS) -- Q-in-Q tagging?

21 june 2013
------------
 - worked on the design a bit more, taking into account link utilization monitoring
 - met with Rudolf, came up with a new structure
 - adapted the introduction and moved some content around to the new structure
 - added some notes and a blueprint, will expand tomorrow

22 june 2013
------------
 - got a lot of definitions on the DVPN stuff
 - finished the Service description, most of the Transport info, blueprint for Provision section

23 june 2013
------------
 - finished first version of DVPN description

24 june 2013
------------
 - worked on graphics and table
 - start on implementation and results

25 june 2013
------------
 - got some feedback from Rudolf, incorporated that
 - added some graphics and content to OpenFlow section
 - installed a VM with [OpenFlow 1.3 implementation from git](https://github.com/CPqD/ofsoftswitch13/wiki/OpenFlow-1.3-Tutorial)
 - tried to get the topology app working in 1.3... so far no luck

26 june 2013
------------
 - wasted more time on the C++ environment
 - improved the intro a little bit
 - met with Rudolf to talk about progress and content
 - made some notes on the comparison

27 june 2013
------------
 - finished the report up until the implementation of OpenFlow

28 june 2013
------------
 - missed an appointment with Rudolf but he hadn't checked the whole report yet anyway
 - besides, got a lot of work done
 - content for implementation done, start of the results, made different graphics
 - incorporated the comments that Rudolf did have into the document

29 june 2013
------------
 - added some facts wrt MPLS FRR
 - some details on OF fast failover
 - explained local significance
 - starting on MPLS/OF comparison

30 june 2013
------------
 - comparison is taking a bit longer than I thought because of details that I need to look up for a factual story.

1 july 2013
-----------
 - created blueprint for presentation text
 - extra info on transport

2 july 2013
-----------
 - first version of presentation
