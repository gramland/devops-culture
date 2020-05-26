# Measuring performance

__A successful measure of performance should have two key characteristics:__
  1. It should focus on global outcome to ensure teams aren't pitted against each other. 
      The classic example is rewarding developers for throughput and operations for stability. 
This is a key contributor to the "wall of confusion" in which development throws poor quality code over the wall to operations 
and the operations put in place painful change management process as a way to inhibit change.
  
  2. Measure should focus on outcomes not output. 
    It shouldn't reward people for putting in large amounts of busy work that doesn't actually help achieving organizational goal. 

## 4 PERFORMANCE METRICS

![Performance metrics](../images/performance_metrics.png)

The first four metrics that capture the effectiveness of the development and delivery process can be summarized in terms of throughput and stability. The study measure the throughput of the software delivery process using __lead time__ of code changes from check-in
to release along with __deployment frequency__. Stability is measured using __time to restore__— the time it takes from detecting a user- impacting incident to having it remediated— and __change fail rate__, a measure of the quality of the release process.

### SOFTWARE DEVELOPMENT

#### Lead time

Lead time is the time it takes to go from a customer making a request to the request being satisfied. 
The elevation of lead time as a metric is a key element of the __Lean__ theory.

#### Deployment frequency

How often does an organization deploy code to production or release it to end users.

### SOFTWARE DEPLOYMENT

### Change fail rate

### Time to restore



## High performers vs low performes



#### When compared to low performers the high performers have (2018): 
  - 46 times more frequent code of deployments 
  - 440 times faster lead time from commit to deploy 
  - 170 times faster mean time to recover from downtime 
  - 5 times slower change failure rate (1/5 as likely for a change to fail)
  
#### When compared to low performers the high performers have (2019): 
  - 208 times more frequent deploy frequency
  - 106 times faster lead time from commit to deploy 
  - 2604 times faster mean time to restore service
  - 7 times Lower Change Fail Rate
  
Source: [state-of-devops-2019](https://github.com/gramland/devops-culture/blob/master/accelerate/pdfs/state-of-devops-2019.pdf)

## Donts

## Measuring productivity

Productivity is the ability to get complex, time-consuming tasks completed with minimal distractions and interruptions.

Measuring productivity in terms of line of code has a long history in software. If you are still doing it stop now (really).
Some companies even require developers to record the lines of code committed per week.
However in reality we would prefer a 10 line solution to a 1000 line solution to a problem.

Rewarding developers for writing lines of code leads to bloated software that incurs in higher maintenance cost and 
higher cost of change. Ideally we should reward developers for solving business problems with a minimum amount of code and it's even
better if we can solve the problem without writing code at all or deleting code or perhaps by a business process change.

Other metrics are often just a way to shift or mask the same problem. 
Measuring quantities that are not statistically correlated with team and organizational perfomance.
Productivity cannot be captured with a simple metric such as lines of code, story points, or bugs closed; doing so results in unintended consequences that sacrifice the overall goals of the team. 
For example, teams may refuse to help others because it would negatively impact their velocity, even if their help is important to achieve organizational goals.
