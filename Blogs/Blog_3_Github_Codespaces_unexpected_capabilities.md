
# Start Coding in Cloud with GitHub Codespaces: Some Unexpected Capabilties

---
<p align="center">
<img src= "https://github.com/Navansh/mlsa-social-impact-projects/assets/58849657/08079c32-6547-4352-ab15-282b8c5f1c5b">
</p>

---

I started to learn to code in my freshman year when C & C++ were introduced in our course curriculum. When I tried to install all the dependencies & code editors on my laptop, I realized it was awfully slow. But I couldn’t afford a better one at that time. Then I tried out browser-based IDEs like onlinegdb.com to run my code.
From that hassle to the present-day scenario, where GitHub Codespaces provides a fully-fledged, cloud-based Integrated Development Environment (IDE) on an instant development environment that uses a container to provide you with common language tools utilities for the development purpose. Internet-powered development is a game-changer for people with less efficient systems but wait- This is just a trailer of GitHub Codespaces’ versatility!
In this blog, I’m going to share a few ways I found useful to utilise GitHub Codespaces!

## Create a customized development environment

Within Codespaces lies the freedom to customize your development heaven. Select your machine type, ranging from 2-core to a staggering 32-core setup. Need a power boost? Opt for a GPU-powered Codespace. Imagine – an iPad or Chromebook becoming a hub for data-intensive machine learning tasks, all thanks to GitHub Codespaces.

<p align="center">
<img src= "https://github.com/Navansh/mlsa-social-impact-projects/assets/58849657/0a47230c-63e2-4441-8c4a-a46762474155">
</p>

## Manage GitHub Codespaces from the command line 

Imagine the times when you unknowingly close your documents, or your computer would suddenly shut down, and all your work is lost. Nowadays, many editors prevent such losses, including GitHub Codespaces. So, if you close a Codespace, it’ll save your work even if you forget to commit the changes.
Also, if you’re done using a Codespace because you pushed your code to the desired repository, you can of course delete it. GitHub Codespace management is important because:
•	You won’t want to get confused among all your GitHub Codespaces and accidentally delete the wrong Codespace.
By default, the inactive GitHub Codespaces are automatically deleted every 30 days.
You can manage your GitHub Codespaces via the GitHub UI or GitHub CLI. Find out more about managing your Codespaces from the command line here!


## Pair programming with teammates made easier

When you’re working remotely, synchronizing with your teammates is challenging. It’s tough to share your screen and your code in real-time when you’re not sitting with a teammate. When we (I & my team) were working on a Social Impact Project, our main concern was how we can pair-program as we were collaborating remotely & had difficulty tracking the changes in the codebase. However, collaboration became easier when a team member Yash suggested using the live share extension. The Live Share extension allows you and your teammate(s) to type in the same project, at the same time. It highlights your teammate’s cursor versus your cursor, so you can easily identify who is typing, and it’s completely secure! We instantly got our problem solved & on this journey, we also improved our communication and technical skills like this. Installing the Live Share extension and forward ports made remote pair programming easier with GitHub Codespaces. 

<p align="center">
<img src= "https://github.com/Navansh/mlsa-social-impact-projects/assets/58849657/49f6aadf-1e67-4448-8138-7819637235bf">
</p>

## Pair program with AI 

You can find numerous extensions on VS Code’s marketplace that are compatible with GitHub Codespaces, including GitHub Copilot. If you want a coding partner, but there’s no one around you, try installing the GitHub Copilot extension to pair-program with AI. GitHub Copilot is an AI-powered code completion tool that helps you write code faster by suggesting code snippets and completing code for you.
Beyond productivity through code completion, GitHub Copilot empowers developers of varied backgrounds. One of my favorite GitHub Copilot tools is “Hey, GitHub,” a voice-activated AI programmer. “Hey, GitHub” improves the developer experience for people with limited physical dexterity or visual impairments.
Learn about more use cases for GitHub Copilot from (Alekhya/Navansh’s blog).

## Teach people to code 

While educating people about coding via bootcamps, classrooms, meetups, and conferences, I’ve learned that teaching people how to code is hard. Sometimes in workshops, attendees spend most of their time setting up their environment so that they can follow along. Instead of expecting beginner developers to understand how to clone repositories to work with a template, they can open a Codespace and work in a development environment you’ve configured. This reduces time, stress, and chaos significantly.
GitHub Codespaces is accessible for teachers and students as it offers 180 hours of free usage. 
See how CS50, Harvard’s largest class, uses GitHub Codespaces to teach students to code.

## Frameworks Made Easy: Learn with Quickstart Templates

Tired of being caught in tutorial loops? GitHub Codespaces' quickstart templates are your launchpad to exploring frameworks.
The Quickstart templates include a boilerplate code, forwarded ports, and a container for experimentation, accelerating your grasp on frameworks and techniques. Dive deep into.application frameworks including Django, React.js, Next.js, Express, Ruby on Rails, Jupyter Notebook & Flask. Templates provide developers with a sandbox to build, test, and debug applications in a codespace. Just one click and you get a template to experiment with a new framework.
Experimenting with a framework in a Codespace helped me to understand React. As I first opened a template, I had no idea about how it works but the boilerplate code helped me to understand the structure of a React file & I experimented on how it works. I even built a small project with it!

<p align="center">
<img src= "https://github.com/Navansh/mlsa-social-impact-projects/assets/58849657/f6a2e476-5a4f-4607-b8f3-eab20715d80c">
</p>


## Store environment variables 

I’ve had messed up with the environment variables many times where I accidentally shared or mishandled my environment variables. I mixed two variable paths & once I couldn’t even figure out a way to share the variable values with my teammates.
Bid adieu to environment variable mishaps now. GitHub Codespaces' secrets keep your sensitive data locked down. Store API keys, credentials, and other secrets with confidence. And with simple references in your code, the process is smoother and more secure than ever before. You can refer to the environment variables in your code as: process.env.{MY_SECRET_API_KEY}.

<p align="center">
<img src= "https://github.com/Navansh/mlsa-social-impact-projects/assets/58849657/4567c8e0-c659-43ad-b395-e74adc5ee843">
</p>

## Revolutionize Onboarding with GitHub Codespaces

No more tedious local environment setup for new team members. Just join a team, launch a Codespace, and dive straight into contributing. This can simplify the process, boost productivity, and embark on a streamlined coding experience.
Conduct technical interviews 
Interviews no longer need to be nerve-wracking experiences. With GitHub Codespaces, create a reliable, configured environment for candidates. Real-time feedback can be provided by interviewers and collaboration are at your fingertips, ensuring a seamless and secure interview process. Also, GitHub Codespaces creates a secure and isolated environment for the interview process, ensuring that sensitive information and data remain protected.
Take a look at how various engineering teams at GitHub use GitHub Codespaces to conduct interviews.

## Code in the cloud with your preferred editor 

Love your editor of choice? GitHub Codespaces caters to various preferences. Beyond Visual Studio Code, explore options like Jupyter Notebook, IntelliJ IDEA, RubyMine, and more. Your coding journey, your rules. Codespaces has made code from anywhere a reality- you can now code even from your smartwatch!

Codespaces isn't just a tool; it's a gateway to a dynamic and boundless coding experience. With up to 60 hours of free access for GitHub users (and 90 hours for GitHub Pro users), the future of coding is right at your GitHub account. Dive into the world of GitHub Codespaces today! What are waiting for? Try it out now

<p align="center">
<img src= "https://github.com/Navansh/mlsa-social-impact-projects/assets/58849657/18f0ee19-5a73-4c81-902e-70dbdb3e57c1">
</p>



