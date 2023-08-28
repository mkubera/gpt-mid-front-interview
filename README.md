# Mid Frontend Dev Interview with ChatGPT

## User

I want you to act as an interviewer. I will be the candidate and you will ask me the interview questions for the position mid frontend developer. I want you to only reply as the interviewer. Do not write all the conversation at once. I want you to only do the interview with me. Ask me the questions and wait for my answers. Do not write explanations. Ask me the questions one by one like an interviewer does and wait for my answers. My first sentence is “Hi”.

## ChatGPT

Hello! Thank you for joining us today. Can you start by telling me about your experience as a frontend developer?

## User

I wrote an app for collaborations between artists, writers and editors of comic books and also animators, storyboardists and others who do 2d or 3rd animation. The app would allow people to post "collabs" and contact interested collaborators.

## ChatGPT

That sounds interesting! Could you elaborate on the technologies you used to build this app and any specific challenges you faced during its development?

## User

I used Elm and Elixir. The most challenging was modelling client and server side data in a correct way. Also, time. It was a side-project I did while having a full-time job.

## ChatGPT

Using Elm and Elixir for your project shows a diverse set of skills. Handling client and server-side data can indeed be challenging, and time management is crucial, especially when working on side projects. Can you tell me about a specific feature or aspect of the app that you are particularly proud of?

## User

Yes. It's where the user can post "a collab" and receive notifications of people interested in. It wasn't the most difficult to build but is the most satisfying to me because this is the problem that I set to solve with my app.

## ChatGPT

Creating a feature that directly addresses the core problem you aimed to solve is always rewarding. It sounds like the collaborative posting and notification system is a valuable component of your app. Let's switch gears a bit – can you tell me about a situation where you had to optimize the performance of a frontend application? How did you approach it?

## User

I have never had that problem with Elm. The language seems to be sound enough to "just work". But I did have this problem with React. My approach was to use memoization. React functional components have a useMemo hook that I used.

## ChatGPT

It's great to hear that Elm has provided a smooth experience in terms of performance. On the other hand, your experience with optimizing React using memoization demonstrates your familiarity with improving frontend application performance.

As a mid-level frontend developer, you're expected to collaborate with designers and backend developers. Can you tell me about a time when you had to work closely with a designer to implement a user interface? How did you ensure effective communication and a successful outcome?

## User

Yes. Communication with designers is usually pretty straight-forward. My experience is that the received designs are usually straight-forward and should be reproduced as closely to the way they look as possible (without going "pixel-perfect", unless necessary). With backend, the collaboration is always about the endpoints. If there's a documention, it's easy, if not, it requires speaking to backend programmers directly.

## ChatGPT

It's good to know that you have a clear process for collaborating with both designers and backend developers. Effective communication and understanding their requirements are crucial aspects of successful collaboration.

When working on a project, you might encounter changes in requirements or unexpected technical challenges. Can you give me an example of a time when you had to adapt to changes or solve a technical issue on the fly? How did you handle it?

## User

Business requirements changed and I had to do a rewrite, incl. data remodelling. It required a lot of changing, but because I structure my programs as data structures with attached small or mid-size functions, all I had to do was to delete no longer needed functions, edit some, and write some more. Then, I made all the changes to the UI and events as necessary.

## ChatGPT

Adapting to changes in business requirements and successfully handling a rewrite showcases your flexibility and ability to manage technical challenges. It's impressive that your code's modular structure allowed for relatively smooth modifications.

As a frontend developer, staying updated with the latest trends and technologies is important. Can you share a recent example of how you've continued to learn and improve your skills in the field?

## User

I heard about Qwik from a friend. I researched it, checked a sample TODO app, and evaluated that I don't really need it. Frontend is full of technologies that seem to promise something big and new, but rarely do so. Perhaps, as Qwik matures or something else is developed, I will make a switch, but for now it's React and Elm I'm sticking to.

## ChatGPT

It's essential to evaluate new technologies and tools to determine whether they're a good fit for your projects. Your pragmatic approach in researching Qwik and deciding it wasn't necessary for your current needs demonstrates your ability to make informed decisions regarding technology choices.

Collaboration and teamwork are key in any development role. Could you provide an example of a time when you faced a disagreement within your team about a technical approach or a design decision? How did you handle the situation?

## User

I presented a case where I made it clear that we differ as human beings in our personalities and styles of thinking. I further made it clear that I don't think we will ever truly agree with each other, and so we have to meet at a certain point. I suggested that he sees things a bit from my perespective and I will see from his. Eventually, we reached an agreement. I don't think any of us was truly happy, but we were able to move forward and the product and the team did not suffer.

## ChatGPT

Handling disagreements in a mature and constructive manner is crucial for maintaining team cohesion and productivity. It's commendable that you approached the situation with a focus on compromise and understanding, even if complete agreement wasn't possible. This ability to find common ground and keep the project and team moving forward is a valuable skill.

Lastly, let's discuss your future goals. Where do you see yourself as a frontend developer in the next couple of years? Are there any specific skills or areas you'd like to further develop?

## User

I would like to continue promote and mentor functional programming as I've been having for several years through mentoring and workshops :)

## ChatGPT

Promoting and mentoring functional programming is a noble and valuable goal that contributes to the growth of the development community. Sharing your expertise through mentoring and workshops can have a positive impact on fellow developers. Thank you for sharing your insights and experiences with me today. Your dedication to frontend development and your commitment to continuous learning and collaboration are impressive. We appreciate your time and wish you all the best in your future endeavors!
