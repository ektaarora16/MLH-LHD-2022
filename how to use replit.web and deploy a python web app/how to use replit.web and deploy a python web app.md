# Introduction: creating an account and starting a project

Visit https://replit.com/signup and follow the prompts to create a user account, either by entering a username and password or by logging in with Google, GitHub, or Facebook.

Once you're done, hit the + new repl button in the top left. In the example below, we choose to create a new Python project. Replit will automatically choose a random name for your project, or you can pick one yourself. Note that by default your repl will be public to anyone on the internet; this is great for sharing and collaboration, but we'll have to be careful to not include passwords or other sensitive information in any of our project files.

![image](https://user-images.githubusercontent.com/90129737/136980424-40b3b6fd-cfaf-49ce-b536-b8de012a64fb.png)


You'll also notice an "Import from GitHub" option. Replit allows you to import existing software projects directly from GitHub, but we'll create our own for now. Once your project is created, you'll be taken to a new view with several panes. Let's take a look at what these are.

# Understanding the Replit panes :

You'll soon see how configurable Replit is and how most things can be moved around to suit your fancy. However, by default, you'll get the following layout.

![image](https://user-images.githubusercontent.com/90129737/136980640-f8625ca6-4d43-4c18-a357-a4115b6a9487.png)


# Left pane: files and configuration:
This, by default, shows all the files that make up your project. Because we chose a Python project, Replit has gone ahead and created a main.py file.

# Middle pane: code editor
You'll probably spend most of your time using this pane. It's a text editor where you can write code. In the screenshot, we've added two lines of Python code, which we'll run in a bit.

# Right pane: output sandbox
This is where you'll see your code in action. All output that your program produces will appear in this pane, and it also acts as a quick sandbox to run small pieces of code, which we'll look at more later.
Run button. If you click the big green run button, your code will be executed and the output will appear on the right.

# Menu bar
This lets you control what you see in the main left pane (pane 1). By default, you'll see the files that make up your project but you can use this bar to view other things here too by clicking on the various icons. We'll take a look at these options later.
Don't worry too much about all of the functionality offered right away. For now, we have a simple goal: write some code and run it.

# Running code from a file

Usually, you'll enter your code as text in a file, and run it from there. Let's do this now. Enter the following code in the middle pane (pane 2), and hit the run button.

print("Hello World")
print(1+2)


Your script will run and the output it generates will appear on the right pane (pane 3). Our code outputs the phrase "Hello World" (it's a long-standing tradition that when you learn something new the first thing you do is build a 'hello world' project), and then output the answer to the sum 1 + 2.

You probably won't be able to turn this script into the next startup unicorn quite yet, but let's keep going.

# Running code from Replit's REPL

In computer programming, a REPL is a read-eval-print loop, and a REPL interface is often the simplest way to run short computer programs (and where Replit got its name).

While in the previous example we saved our code to a file and then executed the file, it's sometimes quicker to execute code directly.

You can type code in the right-hand pane (pane 3) and press the "Enter" key to run it. Take a look at the example below where we print "Hello World" again and do a different sum, without changing our code file.

![image](https://user-images.githubusercontent.com/90129737/136981125-af6d66a2-0362-4e0d-b712-f60816962b96.png)


This is useful for prototyping or checking how things work, but for any serious program you write you'll want to be able to save it, and that means writing the code in a file like in our earlier example.

# Why is deployment necessary?

Your web application must live somewhere other than your own desktop or laptop. A production environment is the canonical version of your current application and its associated data.

# Why Deploy Machine Learning Models?
 
The deployment of machine learning models is the process of making models available in production where web applications, enterprise software and APIs can consume the trained model by providing new data points and generating predictions.

Normally machine learning models are built so that they can be used to predict an outcome (binary value i.e. 1 or 0 for Classification, continuous values for Regression, labels for Clustering etc. There are two broad ways of generating predictions (i) predict by batch; and (ii) predict in real-time. In our last tutorial we demonstrated how to deploy machine learning model in Power BI and predict by batch. In this tutorial we will see how to deploy a machine learning model to predict in real-time.

# Deployment resources

Hello, production lays out the powerful philosophy of putting a project into production as soon as possible in a project's lifecycle to establish the pipeline, identify issues and bottlenecks, and build the foundation for continuous delivery. The post also covers common objections and provides some arguments to help you convince others that this strategy is the right way to go on all projects.

Automated Continuous Deployment at Heroku explains Heroku's deployment system, the checks they use to ensure code quality and what they have learned from building the pipeline and process.

Deploying Python web applications is an episode of the great Talk Python to Me podcast series where I discuss deploying web applications based on a fairly traditional virtual private server, Nginx and Green Unicorn stack.

Thoughts on web application deployment walks through stages of deployment with source control, planning, continuous deployment and monitoring the results.

Deploying Software is a long must-read for understanding how to deploy software properly.

The evolution of code deploys at Reddit teaches the history, including the mistakes, that Reddit's development teams learned as they scaled up the development team and the traffic on one of the most-visited websites in the world.

Deployment strategies defined explains various ways that development teams deploy applications, ranging from reckless to versioned.

How we release so frequently provides a high-level overview of tactics for how teams at large scale can deploy changes several times per day or more with confidence the systems will not completely fail. There will be bugs, but that does not mean the entire operation will stop.

Hands-off deployment with Canary explains how SoundCloud automates their deployment process and uses canary builds to identify and roll back issues to mitigate reliability issues that can occur with shipping software at scale.

Practical continuous deployment defines delivery versus deployment and walks through a continuous deployment workflow.

5 ways to deploy your Python application in 2017 is a talk from PyCon US 2017 where Andrew Baker deploys the getting started Flask app using Ngrok, Heroku, Zappa on the serverless AWS Lambda platform, a virtual machine on Google Cloud and Docker.

Continuous deployment at Instagram is the story of how their deployment process evolved over time from a large Fabric script to continuous deployments. Along the way they encountered issues with code reviews, test failures, canary builds and rollbacks. It's a great read that sheds some light on how Python deployments can be done well at large scale.

Stack Overflow's guide on how they do deployment is an awesome in-depth read covering topics ranging from git branching to database migrations.

TestDriven.io shows how to deploy a microservices architecture that uses Docker, Flask, and React with container orchestration on Amazon ECS.

## Contributors 

- Ekta Arora 
- Shrejal Singh
- Aaquib Ali 
- Ruthvik Kanukunta

