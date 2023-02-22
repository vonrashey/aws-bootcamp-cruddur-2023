# Week 0 — Billing and Architecture

After watching all **Week 00** videos, I worked on the following as part of my homework:

**1. Napkin Design**

This is a general design or sketch of the Cruddur app that I will be building during the bootcamp. Its a basic idea of the application, its input, processes and output requirements. 

![Napkin Design](/../main/assets/LogicalDiagram.png)

**2. Conceptual Diagram**


This is an improved version of the napkin design showing the requirements of the application:

![Conceptual Diagram](https://github.com/vonrashey/aws-bootcamp-cruddur-2023/blob/main/_docs/assets/Conceptual%20Diagram.png)


Link to the Lucidchart Diagram:  [Conceptual-Diagram](https://pages.github.com/)


**3. Logical Diagram**

This is the logical design of the application, showing the building blocks (input, processes and output) of the application at a higher level.

![Logical Diagram](https://github.com/vonrashey/aws-bootcamp-cruddur-2023/blob/main/_docs/assets/LogicalDiagram.png)


Link to the Lucidchart Diagram: [Logical-Diagram](https://pages.github.com/)


**4. Billing Alarm**

I created a  billing alarm during *Chirag's Week 0 - Spend Considerations*. Due to costs involved in creating multiple 


**5. Budget**

I created a  budget alarm during *Chirag's Week 0 - Spend Considerations*. Due to costs involved in creating multiple budgets, I did not create another one.

![AWS Budget](https://github.com/vonrashey/aws-bootcamp-cruddur-2023/blob/main/_docs/assets/Budget.png)


6. Install AWS CLI

I also worked on installing the AWS CLI and saving the environment variables in gitpod. The resulting gitpod.yml file looks like this:

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

8. 
