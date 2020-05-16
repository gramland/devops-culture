# Lean Product development

## Lean product development practices

**DORA (DevOps Research and Assessment)** examine 4 capabilities which relates to **LEAN** approach to product development. 

  1. The extent to which teams slice up products and features into **small batches** that can be completed in less than a week and released frequently, including the use of MVPs minimum viable products.
  2. Whether teams have a good understanding of the flow of work from the business all the way through to customers, and whether they have visibility into this flow, including the status of products and features. 
  3. Whether organizations actively and regularly seek customer feedback and incorporate this feedback into the design of their products. 
  4. Whether development teams have the authority to create and change specifications as part of the development process without requiring approval. 
  
## Theme experimentation

If a development team isn't allowed, without authorization from some outside body, to change requirements or specifications in response to what they discover, their ability to innovate is sharply inhibited. 

Effective product management drivers performance. 
Furthermore, the ability to take an experimental approach to product development is highly correlated with the technical practices that have contributed to continuous delivery. 
Making work sustainable. 


## Deployment pain 

If your teams have no visibility into code deployment -which means that if you ask your teams what software deployments are like and the answer is "I don't know... I've never thought about it"- that's another warning that software delivery performance could be low, because if developers or testers, aren't aware of the deployment process, there are probably barriers hiding the work from them. 

Barriers that hide the work of deployemnt from developers are rarely good, beacuse they isolate developers from downstream consequences of their work.

Improving key technical capabilities reduce deployment pain. 
Teams that implement comprehensive test and deployment automation, use continuous integration including trunk-base development, shift left on security, effectively manage test data, use loosely coupled architecture, can work independently, use version control of everything required to reproduce production environments, decrease their deployment pain. 

Put another way the technical practices that improve our ability to deliver software with both speed and stability also reduce the stress and anxiety associated with pushing pushing code to the production. 

### How painful deployments are?

If you want to know how your team is doing just ask your team how painful deployments are and what specific things are causing that pain. 

Fundamentally, most deployment problems are caused by a complex brittle deployment process. 
Manual change can easily lead to errors caused by typing, copy/paste mistakes or poor or out-of-date documentation.

Environments whose configuration is managed manually often deviate substantially from each other (a problem known as "configuration drift). 

In order to reduce deployment pain we should:
  * Build systems that are designed to be deployed easily into multiple environments, can detect and tolerate failures in the environments and can have various components of this system updated independently
  * Ensure that the state of production systems can be reproduced (with exception of production data) in an automated fashion from information in version control.
  * Build intelligence into the application and the platform so that the deployment process can be as simple as possible. 


## Burnout

Burnout is physical mental or emotional extortion caused by overwork or stress. 

Burnout can make things we once loved about our work and life seem insignificant and dull. 
The consequences of burnout are huge for individuals and for their teams and organization.

Researches show that stressful job can be as bad for physical health as secondhand smoke.
Symptoms of burnout include feeling exhausted, cynical, ineffective, little or no sense of work accomplishment, feelings about work negatively affecting other aspects of life. 

In exgtreme cases burnout can lead to family issues, clinical depression, suicide.

To advert employee burnout, managers should concentrate their attention and efforts to:
  * fostering a respectful, supportive work environment that emphasize learning from failures rather than blaming
  * communicating a strong sense of purpose 
  * investing in employee development 
  * asking employees what is preventing them for achieving their objectives and then fixing those things 
  * giving employees time, space and resources to experiment and learn

Last but not least, employees must be given the authority to make decisions that affected working their job particularly in areas where they are responsible for the outcome. 


### How to reduce or fight burnouts 

  1. Organizational culture 
    Managers should also watch for other contributing factors and remember that human error is never the root cause of failure in the system. 
  2. Deployment pain 
    Complex painful deployments that must be performed outside of business hours contribute to high stress and feeling of lack of control   3. Effectiveness of leaders
    Responsibilities of a team leader include limiting work in the process of eliminating roadblocks for the team so that they can do the work done.
  4. Organizational investment in DevOps 
    Organizations that invest in developing the skills and capabilities of their teams get better outcome. 
    Investing in training and providing people with the necessary support and resources, including time, to acquire new skills are critical to the seuccessful adoption of DevOps.
  5. Organizational performance
    Lean management and continuous delivery practices improve software delivery performance which in turn improve organizational performance.
    
At the heart of Lean management is giving employees the necessary time and resources to improve their own work. 

This also means creating space for employees to do new creative value at work during the work week and not just expecting them to devote extra time for after hours. 

In summary DORA research found evidence that technical and **Lean** management practices contribute to reduction in both burnout and deployment pain. 
