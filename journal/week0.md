# Week 0 — Billing and Architecture

After watching all **Week 0** videos, I worked on the following as part of my homework:

**1. Napkin Design**

This is a general design or sketch of the Cruddur app that I will be building during the bootcamp. Its a basic idea of the application, its input, processes and output requirements. 

![Napkin Design](./assets/Week%200/Napkin%20Design.jpeg)

**2. Conceptual Diagram**


This is an improved version of the napkin design showing the requirements of the application:

![Conceptual Diagram](./assets/Week%200/Conceptual%20Diagram.png)


Link to the Lucidchart Diagram:  [Conceptual-Diagram](https://lucid.app/lucidchart/2c00f7d2-b3f1-4964-90c8-bc1b92ea37ed/edit?viewport_loc=-297%2C-113%2C1972%2C800%2C0_0&invitationId=inv_53f6ebdd-9b7d-416e-bc8c-33e874b8f80e)


**3. Logical Diagram**

This is the logical design of the application, showing the building blocks (input, processes and output) of the application at a higher level.

![Logical Diagram](./assets/Week%200/LogicalDiagram.png)


Link to the Lucidchart Diagram: [Logical-Diagram](https://lucid.app/lucidchart/5ebdc455-cfa5-42e1-9e52-1a4a1a4a493e/edit?viewport_loc=296%2C5%2C2220%2C1000%2C0_0&invitationId=inv_8f04a44b-31c1-470e-96aa-15f0496a8fda)


**4. Billing Alarm**

I created a  billing alarm during *Chirag's Week 0 - Spend Considerations*. 

![Logical Diagram](./assets/Week%200/Billing%20Alarm.png)


**5. Budget**

I created a  budget alarm during *Chirag's Week 0 - Spend Considerations*. Due to costs involved in creating multiple budgets, I did not create another one.

![AWS Budget](./assets/Week%200/Budget.png)


**6. Install AWS CLI**

I also worked on installing the AWS CLI and saving the environment variables in gitpod. The resulting `gitpod.yml` file looks like this:


```
tasks:
  - name: aws-cli
    env:
     AWS_CLI_AUTO_PROMPT: on-partial
    init: |
      cd /workspace
      curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
      unzip awscliv2.zip
      sudo ./aws/install
      cd $THEIA_WORKSPACE_ROOT
```

*Admin user, IAM user were already created. Sample user generated credentials are shown below*

![User Credentials](./assets/Week%200/gitpod%20user.png)
