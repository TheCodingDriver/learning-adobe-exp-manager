Adobe Experience Manager

Learning AEM While Working on a Giving Season Requirement
When I started working on Fidelity Charitable, I came across a requirement that was quite different from the usual backend development work I had been doing.

During the giving season, some of the information displayed in our application needed to be updated frequently. The challenge was that these updates should not require a new application deployment every time. The business wanted the front desk or content team to be able to make changes themselves, without depending on developers for every small update.

Until then, most of my experience had been with Java, Spring Boot, REST APIs and databases. I was comfortable building backend services, but I had very limited knowledge of Adobe Experience Manager (AEM).

Initially, I thought we could handle the requirement through our existing backend configuration or database. That would have been a familiar approach for me, but it would still require technical involvement whenever the content changed. After discussing the requirement further, I understood that the main problem was not just fetching the data. It was about giving the business team control over the content without changing the application code.

That was when I started learning AEM.

I didn't try to learn the entire platform. I first focused on understanding how content is created, maintained and published in AEM, and how an application can retrieve that content.

I spent time going through the existing AEM setup, reading documentation and discussing a few things with team members who had worked on it before. I also explored how content fragments and content models work, since they were relevant to the kind of information we wanted to manage.

Once I had a basic understanding, I started looking at how we could fetch the required content from AEM and make it available to our application.

One thing I realized during this work was that I had initially spent too much time trying to understand everything on my own. I could have approached it better by identifying the areas where I needed help and involving the right team members earlier. For example, understanding the content structure, the publishing process and the application integration could have been discussed separately. That would have saved some time.

As I progressed, the overall flow started making more sense. The content team could maintain the information in AEM, publish the changes, and our application could retrieve the updated content without requiring a new code deployment.

This was particularly useful for the giving season because business information could change at short notice, and waiting for a development and release cycle was not practical.

I felt I had caught up with the technology when I could understand the complete flow, from content creation in AEM to retrieving and displaying it in our application. More importantly, I was comfortable working on the integration and discussing changes without having to depend on someone else for every small issue.

I wouldn't say I became an AEM expert in a short time, but I learned enough to contribute to the requirement and understand how the technology fitted into our application.

The biggest learning for me was that sometimes the difficult part of a new technology is not writing the code. It is understanding why the technology is being used and how it solves a business problem.

In this case, AEM helped us separate content changes from application deployments, which made the process more flexible for the business team.

It was also a reminder that when working with something unfamiliar, I should focus on the immediate requirement, ask for help early and learn through implementation rather than trying to understand every feature before starting.
