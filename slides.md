---
theme: apple-basic
layout: intro-image
image: >-
  https://images.unsplash.com/photo-1616004655123-818cbd4b3143?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80
---

<div class="absolute top-10">
  <span class="font-700">
    Ivan Khanevich, 2022
  </span>
</div>

<div class="absolute bottom-10 bg-dark-900 bg-opacity-70 rounded-xl px-5">
  <h1>API-first approach</h1>
  <p>in software development</p>
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
      With an API-first approach, instead of starting with code, you could start with design, planning, mocks, and tests. It allows gathering feedback at this early stage allows you to make changes more easily before a lot of time and effort is sunk  into the project.
    </p>
</section>

<section>
  <img src="https://miro.medium.com/max/2000/1*sfzD7ASe-ESAwU06yOYblA.png" class="h-60" />
</section>

---

# Props of an API-first approach

<section class="max-w-screen-sm">
  <p>
    This approach takes it a step further and requires planning the intended API’s functionality before building the API
    itself. What functionality will the API have? What data will it expose? What will the developer experience be like?
    How will it scale? How will we add new functionality in the future?
  </p>

  <ul>
    <li>Development teams can work in parallel</li>
    <li>Ensures good developer experiences</li>
    <li>Earlier validation</li>
    <li>Documentation</li>
  </ul>
</section>

---

<section class="max-w-screen-sm text-red-500">
  <h1>Word of Caution</h1>
  <p>
    Focusing on the design first does not mean ruminating endlessly on all the what-if scenarios. A good design should have the flexibility to adapt to changing circumstances and accommodate new insights. As some teams can attest, mandating that specifications drive development can backfire.
  </p>
</section>

---

# Useful links

- [Design and Prototype an API in Postman](https://youtu.be/r4kb3jOSsmk)
- [API-first software development for modern organizations](https://medium.com/better-practices/api-first-software-development-for-modern-organizations-fdbfba9a66d3)
- [Design APIs like you design User Experience](https://medium.com/better-practices/design-apis-like-you-design-user-experience-a7adeb2ee90f)
- [API Design Guide](https://www.postman.com/postman/workspace/postman-team-collections/documentation/1372588-81512aa8-f91a-4bcd-a53a-6037780c730e)
