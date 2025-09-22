# TableauNext-Hackathon-Customer-Health-Pulse-Predict-Prevent-Protect
It as a “Tableau Next analytic app built on Salesforce”, designed by using Tableau Next inside the provisioned Salesforce org with a semantic model, metrics, and dashboards, plus Agentforce actions.
Customer Health Pulse uses Tableau Next to combine CRM, support, product usage, and Slack data into a single health score. In order for teams to take early action, stop attrition, and save client relationships, it anticipates at-risk accounts, identifies underlying issues, and initiates Slack playbooks.

## Inspiration
The motivation was, the problem that customer success teams deal with on a daily basis: churn's early warning signs are scattered throughout several systems, including CRM, support, product usage, and Slack. Frequently, it is too late when the signals appear. Our goal was to create a system that could not only visualize these signals but also convert them into account-saving actions.

## What it does?
Customer Health Pulse uses Tableau Next to create a single health score that integrates CRM, support cases, product usage, and Slack interactions. It provides proactive Slack notifications with customized playbooks, identifies at-risk accounts, and explains the underlying reasons. This transforms analytics into actionable steps that help teams reduce attrition and protect profits.

## How we built it?
- A synthetic dataset comprising 200 client accounts with realistic activity patterns was created.

- Created a Health Score model that combines recent interaction, Slack mentions, usage hours, support cases, and logins:

  ** HealthScore=(Logins×2)−(SupportCases×5)+(SlackMentions×3)+(UsageHours×0.5)−(LastEngagementDaysAgo×0.5) **

- Created an interactive Tableau Next dashboard that includes root cause analysis, top at-risk customers, account distribution, and KPIs.

- Sent real-time notifications when clients fall into the "At Risk" category by integrating with Slack through a webhook.

- Playbook suggestions were created to help teams take the appropriate retention measures.


## Challenges we ran into
- Generating artificial intelligence data that is realistic enough to mimic consumer behavior and draw attention to health trends.

- Demonstrating value while streamlining Slack integration to meet the hackathon schedule.

- Putting features first and avoiding over-engineering in favor of a distinct MVP.

## Accomplishments that we're proud of
- A functional end-to-end pipeline that includes data, health score, dashboard, Slack alert (tried but with limited access to my account, was not able to generate alerts), and playbook with AgentForce.

- Transforming Tableau Next into an action-driven agentic system instead of just a visualization tool.

- Creating a pristine, well-executed demo in a matter of days.

## What we learned?
- The significance of using data to tell a story—it's not just about numbers; it's also about demonstrating their significance.

- How to go from insight to action to impact using Tableau Next and Slack together.

- Scoping's power: concentrating on an MVP rather than attempting to create everything at once can yield greater benefits.

## What's next for Customer Health Pulse: Predict, Prevent, Protect
- Incorporate sentiment analysis from Slack, emails, and support tickets to gather qualitative indicators.

- Make use of machine learning models to forecast churn in a predictive manner.

- To further cut down on manual labor, integrate with Salesforce workflows to automatically initiate retention steps




<img width="975" height="917" alt="image" src="https://github.com/user-attachments/assets/b7dbb1bd-4219-4770-8f02-970d65989af9" />










