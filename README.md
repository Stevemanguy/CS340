Maintainable, readable, adaptable:
I keep code maintainable by separating responsibilities, using clear names, and reusing components instead of duplicating logic. In this course, the CRUD module from Project One was the best example of that. It kept MongoDB connection and query behavior in one place, so the 
Project Two dashboard code could focus on the UI and callbacks. The advantage was easier debugging and cleaner changes. In the future, I can reuse the same CRUD module for other dashboards or scripts that need the same database operations without rewriting database code.

Approach as a computer scientist:
I start by turning requirements into a checklist and building the smallest working version first. For this project, I verified the database connection and “read all” worked, then added filters. Then I ensured the table and charts updated correctly, and finally tested each 
required filter state for screenshots. This felt more like real client work than some earlier assignments because usability and proving functionality mattered, not just getting a program to run. Going forward, I’ll keep using incremental development and early testing to 
reduce mistakes and make changes safer.

What computer scientists do and why it matters:
Computer scientists design systems that make data usable and reduce manual work and error. A dashboard like this helps Grazioso Salvare work faster and more accurately because users can filter and visualize shelter data without writing database queries. That makes better 
decisions easier and saves time, which directly supports the organization’s mission.
