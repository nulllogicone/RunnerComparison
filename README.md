# RunnerComparison

> Compare all kind of task runner, action orchestrator, user journey builder, business workflow executor, ....

### Runner examples

- GitHub actions  .yml
- DevOps pipelines  .yml
- LogicApps .json
- Durable Functions (async -> queue -> table)
- B2C custom policies .xml

Those are 'task runners' for 'business workflows'. Nice!
Similar but different. 


#### GitHub actions

- CI/CD and task automation platform
- Integrates directly with GitHub repositories
- YAML-based workflow configuration
- Marketplace with pre-built actions
- Use case: Automating software development workflows and CI/CD pipelines

#### DevOps pipelines

- CI/CD service within Azure DevOps
- Build, test, and deploy code to various platforms
- YAML or visual designer for pipeline configuration
- Integrates with Azure and third-party services
- Use case: End-to-end CI/CD pipelines for various development scenarios

#### Logic Apps

- Workflow-based integration service
- Visual Designer and Connectors
- JSON-based language for defining workflows
- Serverless architecture
- Use case: Complex, long-running, and event-driven workflows

#### Durable Functions

- Serverless compute service
- Event-driven and scalable architecture
- Supports multiple languages (C#, JavaScript, Python, etc.)
- Trigger-based execution (HTTP, Timer, Queue, etc.)
- Use case: Executing small, stateless pieces of code in response to events

#### Azure AD B2C

- Cloud identity management service
- Policy-driven framework using XML
- Customizable user experience
- Integration with various identity providers
- Use case: User authentication, authorization, and profile management

#### B2C user journey custom policy .xml

> How do you think is the runtime of B2C handled under the hood?  
> I've seen a nice presentation how LogicApp Standard does it *under the hood*, like Durable Functions - with all the queue- and table behind the scene for event-sourced-async handling.
>   
> But B2C? Must be a transcoder from Xml to a 'realtime runner' (complete opposite to LogicApps)

... I copied the above paragraph to ChatGPT and the result was mind-blowing and resulted in a powerpoint story line.

todo:copy ChatGpt chat






### Summary

Slide 7: Comparison  

Create a table comparing key aspects of Logic Apps, AD B2C, GitHub Actions, and DevOps Pipelines, such as:
Purpose: Integration vs Identity Management vs CI/CD and Task Automation
Language: JSON vs XML vs YAML
Architecture: Workflow-based vs Policy-driven vs Event-driven
Key features: Connectors, Visual Designer vs Customizable UI, Identity Providers vs GitHub Integration, Marketplace vs Azure Integration, Visual Designer  

Slide 8: Integration and Scalability

Explain how all services integrate seamlessly with other Azure services, GitHub, and third-party solutions
Highlight the scalability and high availability of each service

Slide 9: Conclusion  

Summarize the key differences and similarities between Azure Logic Apps, Azure AD B2C, GitHub Actions, and Azure DevOps Pipelines
Emphasize that each service is designed for different purposes and provides secure, scalable, and highly available solutions for their respective use cases

## Future

What comes next? 
At the moment of writing ChatGPT arised as the *next big thing*. So here I just want to mention that a "large language model" is great to translate between all the above examples.
