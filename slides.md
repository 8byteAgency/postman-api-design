---
theme: "apple-basic" 
layout: "intro-image"
image: "https://images.unsplash.com/photo-1616004655123-818cbd4b3143?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
---

<div class="absolute top-10">
  <span class="font-700">
    Ivan Khanevich, 2022
  </span>
</div>

<div class="absolute bottom-10 bg-dark-900 bg-opacity-70 rounded-xl px-5">
  <h1>API-first approach</h1>
</div>

---

# When the code comes first

<section class="max-w-screen-sm">
  <p>
    With a code-first approach, you might start with your integrated development environment (IDE) to type out a few lines of code. Somewhere in the back of your mind, you know that eventually an interface will be created to deliver this service. However, your main focus is on what you call “core functionality” not the “interface”.
  </p>
</section>

<section>
  <img src="https://miro.medium.com/max/2000/1*K2MYLutCoDf6HUXQ5tjB1w.png" class="h-60" />
</section>

---

# What we have in our case

- Frontend team don't know how the API will look like, until the backend team implement it;
- It is not always possible for the backend team to properly plan what APIs are needed;
- Main focus of backend team is on “core functionality”, so it drives the implementation of the API;
- Besides, a disjointed developer experience, this approach leaves your team vulnerable to bottlenecks;

---

# When the API comes first

<section class="max-w-screen-sm">
    <p>
      With an API-first approach, instead of starting with code, you could start with design, planning, mocks, and tests.
    </p>
    <p>
      Gathering feedback at this early stage allows you to make changes more easily before a lot of time and effort is sunk  into the project. Using mocks or an API development environment makes the current state of the project more accessible to both technical and non-technical team members.
    </p>
    <p>
        By also separating the design of the API from its implementation, the architect is constrained only by the data model and business logic. Your API can now evolve unfettered by any existing user interface or legacy engineering frameworks.
    </p>
</section>

---

# Props of an API-first approach

<section class="max-w-screen-sm">
  <p>
    This approach takes it a step further and requires planning the intended API’s functionality before building the API itself. What functionality will the API have? What data will it expose? What will the developer experience be like? How will it scale? How will we add new functionality in the future?
  </p>
  <p class='text-red-500'>
    <b>Word of Caution:</b> focusing on the design first does not mean ruminating endlessly on all the what-if scenarios. A good design should have the flexibility to adapt to changing circumstances and accommodate new insights.
  </p>
</section>

- Development teams can work in parallel
- Ensures good developer experiences
- Earlier validation
- Documentation
