# Midterm Project

Alchemy Code Lab, Devsign Career Track, Winter 2018

## Project Description

By 1 pm next Friday, February 9, your team will present a completed app demonstrating the techniques we've covered thus far in class.

* Make it responsive, using a combination of CSS Grid and Flexbox.
* Follow component and router architecture we've used on other labs.
* Use Webpack for development and production builds
* Allow users to sign up and sign in, using Firebase authentication system.
* Store user data using:
  * Realtime Firebase Database
  * Firebase Cloud Storage for files and images
* Protect parts of the app from unauthorized access and generally enforce "doing the right thing"
* Implement responsive image loading strategies.
* Apply the principles of Chapter 3 of *Don't Make Me Think!* to make body copy scan-friendly.
* **Test** users along the way to make sure you're on the right track.
* Be mindful of places where subtle CSS animations could aid usability.

Your final app should be deployed to Firebase _and/or_ Github pages for presentation.

---

## Initial Requirements

Review your notes on the research/discovery and strategy phases of the UX process. **By Monday morning**, you should have completed the following:

### Competition Analysis

Who are your direct competitors? Your indirect competitors? What are the strengths and weaknesses of those competitors?

### User Personas

Describe the circumstances of the use of your app. For each persona, include

* Name and photo
* Level of technical expertise
* Typical browsing behaviors
* Goals while using your site

### UX Strategy Document

Remember to keep your strategy brief, two pages maximum. This should include

* **A vision statement**, stating the goals of this project and the benefits users can expect from your product
* **Circumstances of use**, which is a brief summary of work done in your personas. Who uses this app, and under what conditions?
* **UI design criteria**. What are your interface design goals?
* **Success metrics**. How would you measure whether your product is successful?

Think carefully about user **stories** here: 

* How would each user find your app in the first place? 
* What would they have in mind as they arrive? 
* What specific steps would they take in (hopefully) arriving at their goal? 
* What discoveries might they make along the way?

Your answers to these questions will help determine how you structure your content and data.

## Ongoing Technical Design Requirements

### App Routes and Subroutes

Create and maintain a high-level diagram of the routes and subroutes of your application. You should have an initial draft by end-of-day Monday

### Component Design

These steps can occur JIT (just-in-time) for the different vertical slices:

1. Decompose your designs into distinct components
1. Create tree-diagrams of your components and show the flow of data from firebase, the url, and parent-to-child data passing (including callback functions)
