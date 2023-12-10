# Chirp

To start your Phoenix server:

  * Run `mix setup` to install and setup dependencies
  * Start Phoenix endpoint with `mix phx.server` or inside IEx with `iex -S mix phx.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](https://hexdocs.pm/phoenix/deployment.html).

## Learn more

  * Official website: https://www.phoenixframework.org/
  * Guides: https://hexdocs.pm/phoenix/overview.html
  * Docs: https://hexdocs.pm/phoenix
  * Forum: https://elixirforum.com/c/phoenix-forum
  * Source: https://github.com/phoenixframework/phoenix

Phoenix Framework Final Project Documentation

Project Overview

Contributors: 
Kyler Smith 
Lucas Rowsey

Project Description

The goal of our project was to create a social media demo, inspired mostly by twitter and instagram, utilizing the Phoenix Framework with the Elixir programming language. We aimed to showcase the ease and efficiency of implementing Phoenix Framework for real-time applications, specifically leveraging LiveView to enhance the development process. 

GitHub Repositories

Our project is hosted on GitHub. You can find the repositories at 
https://github.com/Kbsmitty/instagramClone 
https://github.com/lrowsey/PhoenixFramework

Project Objectives 

Our primary objective was to develop a demonstrative social media application similar to Twitter. The focus was on leveraging the capabilities of the Phoenix Framework to streamline the development process, making it more efficient and less labor-intensive. 

Technology Summary

Phoenix Framework

Phoenix Framework is a powerful web framework for Elixir that enables the development of real-time applications. The framework is known for its efficiency and scalability, making it an ideal choice for projects requiring real-time features. 

LiveView

LiveView, a key feature of Phoenix Framework, allows developers to create interactive, real-time user experiences without the need for JavaScript. It simplifies the development of dynamic, responsive web applications. 

When a browser makes an http request so a server that is hosting the single page app, html is returned then the browser requests the javascript and css that are in the html fire. If the single page app doesn’t support server side rendering then the browser may have to request more data before the app is rendered in the browser. 

When you make an http request to a Phoenix live view URL, what is sent back from the server is the page's fully rendered html which provides a fast page load similar to a multi page app. Unlike a multi page app or a single page app, things like data state (what is happening to the data), client logic (functions for events), and view functions (the html) are held on the server instead of the browse through a websocket connection and are all called the LiveView Process. This allows for Phoenix LiveView to be less complex than something like a single page app. 
Demo Application

The demo application simulates a social media platform where users can post updates, follow other users, and engage in real-time conversations. Leveraging LiveView, we aimed to provide a smooth and dynamic user experience. 

How to Run the Project

To run the project locally, follow these steps: 
Clone the GitHub repository: ‘git clone https://github.com//Kbsmitty/instagramClone.git’
Navigate to the project directory: ‘cd instagramClone’
Install dependencies: ‘mix deps.get’
Set up the database: ‘mix ecto.setup’
Start the Phoenix server: ‘mix phx.server’

	Visit ‘http://localhost:4000’

Key Takeaways

While learning how to use and navigate the phoenix framework my biggest takeaway was the difference between learning older established software and new software. It was interesting to learn something that was very new ,it definitely had some cool features, but the lack of documentation was very challenging. Compared to something like java, c or html there were not a ton of resources to help learn. When I did find a good resource it was often outdated because it is still being developed and the changes are so large parts of the older versions are no longer relevant. Overall it was definitely an interesting experience and I think it gave me some good insight on learning new kinds of software. 

Contributions
I made a twitter clone on the pheonix framework. Kyler and I helped eachother initially because the proccess of setting up both of the webcites was fairly similiar. I then went and added a few new features like the edit and delete function we did most of the work in a call together offering help when needed. I also did half of the slideshow.

Resources
Phoenix Framework Official Website
https://www.phoenixframework.org/
Phoenix Framework Documentation
https://hexdocs.pm/phoenix/overview.html
Phoenix Framework GitHub Repository
https://github.com/phoenixframework/phoenix

