# CS255

### Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

Driver Pass was a project for a small company, that was looking to offer a solution that the founder realized there was no great existing solution for. The problem, was that as everyone was required to take a drivers license test, there wasn't much preparation material, training, practice tests, etc. We were hired to develop a system that did exactly that. Our needed to exist at first as a very limited, sales funnel type website. Then, when the user logs in, a transformation needs to occur, incredibly fast. A functional dashboard, that powers all of those components and is still easy to use? That’s what made this project challenging. 



### What did you do particularly well?

For me, I believe I had some really great ideas surrounding how the system architecture should look. I think a cloud provider is absolutely the best way to go, and a cluster of instances running in parallel, across many regions is an incredible way to have strong performance, while also being redundant. 



### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would maybe revise my Use Case Diagram. I like how it is now, but I think if I had more time, and did another pass I could find many more use cases to include. That diagram is incredibly useful and one of my favorites, but its not nearly as complete as I thought it was. 



### How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?

I really try to imagine several different types of people using what i’m designing. In this project, that was particularly easy to do because of the starting interview transcript. While reading that transcript, i was able to take notes on all the different peoples concerns, requirements, and suggestions. You never want to create a solution without taking into account who will be using it. At the end of the day you are creating a tool, and if no one knows how to use it, it will never be used. 


### How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

I like to take my time when designing software, if possible. I like to start from the top down, and break the solution into distinct components. For example, here, I immediately thought: “web-based,  probably an app, a cloud powered backend, and a fast api connection for communication.” While this doesn’t even begin to explain the entire solution, for me it acts as a really great starting point.

From there, I would then focus on each component once at a time. Really go deep on a digestible chunk of the design, and once finished, begin to analyze those components and how they are intertwined. 

