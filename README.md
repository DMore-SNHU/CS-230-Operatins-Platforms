# CS-230-Operatins-Platforms

1. Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room was the client, and they wanted to expand their Android-only game, Draw It or Lose It, into a web-based application that could run across multiple platforms. The game allows multiple teams and players to compete in guessing stock image-based drawings under time constraints. Their requirements included scalability, unique identification for games, teams, and players, cross-platform compatibility, and secure, real-time interactions 
.

2. What did you do particularly well in developing this documentation?
I did well in clearly outlining the requirements and translating them into technical and design solutions. I also effectively applied design patterns such as the Singleton (to manage a single game service instance) and the Iterator (to ensure name uniqueness), which strengthened the overall architecture and demonstrated object-oriented principles.

3. What about the process of working through a design document did you find helpful when developing the code?
The design document provided a structured roadmap for development. By identifying the requirements, constraints, and architecture beforehand, it reduced ambiguity when coding. For example, knowing that a Singleton was required for the GameService made the implementation straightforward and ensured consistency across sessions.

4. If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
If I could revise one section, it would be the Evaluation section. While I analyzed the strengths and weaknesses of different platforms, I would expand it with more concrete examples and benchmarking data to make a stronger case for Linux as the server platform.

5. How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
The client’s needs—cross-platform support, unique identification of entities, and scalability—were directly implemented into the design by using platform-independent technologies (e.g., Java, web frameworks), enforcing uniqueness via iterators, and planning for distributed systems. Considering user needs is essential because the software must solve their specific problem, not just be technically sound. Without aligning with user needs, the solution would risk being impractical or unsatisfactory.

6. How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
I approached the design using object-oriented principles (inheritance, encapsulation, polymorphism), combined with design patterns like Singleton and Iterator, to enforce maintainability and scalability. I also structured the design document around the client’s requirements, constraints, and recommended architecture. In the future, I’d continue using this requirements-driven approach, supported by UML diagrams and architecture planning, to ensure clarity before coding begins.
