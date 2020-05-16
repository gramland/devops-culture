# Lean management and monitoring capabilities


* Have a lightweight change approval process
* Monitor across application and infrastructure to inform business decisions
* Improve processes and manage work with work-in-progress (WIP) limits
* Visualize work to monitor quality and communicate troughout the team

## Lean management practices 
Lean management and its application to software delivery are modeled by three components.

1. Limiting work in progress and using these limits to drive process improvement and increased throughput.
2. Creating and maintaining visual displays showing key quality and productivity metrics and the current status of work (including defects), making these visual display available to both engineers and leaders, and aligning this metrics with operational goals.
3. Using data from application performance and infrastructure monitoring tools to make business decision on daily basis. 

When WIP limits are combined with use of visuals dispalys, feedback loop from production monitoring tools back to delivery teams there is a stronger positive effect.


## Implement a lightweight change management process 

Teams that reported no approval process or used peer review achieved higher software delivery performance. Teams that required approval by an external body achievedlower perfomance.

External approvals are negatively correlated with lead time, deployment frequency, and restore time, and had no correlation with change failure rate. 
Approval by an external body (such as a manager or CAB) simply doesn't work to increase the stability of production systems,
measured by time to restore service and change fail rate. It definitely slow things down. 
It is in fact worse than having no change approval process at all. 

**DORA (DevOps Research and Assessment)** recommendation based on this result is to use a lightweight change approval process based on peer review such as pair programming or intrateam code review combined with the deployment pipeline to detect and regect bad changes.

This process can be used for all kinds of changes including code infrastructures and database change. 


### Segregation of duties

In regulated Industries segregation of duties is often required either explicitly in the wording of the regulation or by auditors. 

There are two mechanism which can be effectively used to satisfy both the latter and the spirit of this control.
  1. When any kind of changes is committed, somebody who wasn't involved in authoring the change should review it either before or immediately following commit to version control. 
  2. Change should only be applied to production using a fully automated process that forms part of a deployment pipeline. 

On the other way, the idea that an external body not intimately familiar with the internals of the system can review tens of thousands of lines of code change by potentially tens or hundreds of Engineers and accurately determine the impact on complex production system it is not realistic. 

This idea is a form of risk management theater. Somenone check boxes so that when something goes wrong we can say that at least we follow the process. 

At best this process only introduced time delays and handoffs. 
