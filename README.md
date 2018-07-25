<p align="center">
  <img src="https://design.fastwork.co/_nuxt/img/fw-logo-full-mono-600x100.0dfad36.png" width="600">
</p>

# { "developer": "Mobile Engineer (Native)" } to Fastwork

Objective of this challenge is to evaluate your domain in **Mobile application development (Swift or Kotlin)**, that is, its organization, style and good practices with the code, creation of application, knowledge of the frameworks and technologies used.

## Rules

1. Please organize, design, test, document and share your app, then send us a link to the hosted repository (e.g. Github, Bitbucket...).

2. Develop the project using:
    - **Swift or Kotlin**

3. Submit the link of your repository with the challenge code until **10 days** after its application.

## The challenge

Here is the layout and description that should be produced:

**Create product list page.**

<img src="product-list-header2.png" width="250">
<br/>
<img src="product-list3.png" width="250">

- Create header, tab bar, taxonomy filters.
- Filter button can click to show blank popup.
- Each product list can click to product detail.
- Product list data can render this api http://www.mocky.io/v2/5b0275b83000007500cee151

<br/>

**Create product detail page.**

<img src="product-detail.png" width="250">

- Create layout and fill data.
- Back button can click to product list.
- Ignore all action on this page such as click favorites, share, etc.

> More detail UI layout can send your questions directly to [burin@fastwork.co](mailto:burin@fastwork.co).

### APIs

Using our api for get data.

#### [GET] product list and detail
- http://www.mocky.io/v2/5b0275b83000007500cee151

### Some tips and remarks

> Note 1: Feel free to use any 3rd party, be it for graphics, tests, etc;

> Note 2: Consider that all fields are mandatory in the form.

> Note 3: Consider validating the fields also in the API and in case of inconsistency return error in a structured JSON with HTTP 400 code

## Readme

Write your README as if it was for a production service. Include the following items:

* Description of the problem and solution.
* Whether the solution focuses on back-end, front-end or if it's full stack.
* Reasoning behind your technical choices, including architectural.
* Trade-offs you might have made, anything you left out, or what you might do differently if you were to spend additional time on the project.

## How we review

Your application will be reviewed by the CTO and at least one senior engineer. We do take into consideration your experience level.

**We value quality over feature-completeness**. It is fine to leave things aside provided you call them out in your project's README. The goal of this code sample is to help us identify what you consider production-ready code. You should consider this code ready for final review with your colleague, i.e. this would be the last step before deploying to production.

The aspects of your code we will assess include:

* **Architecture**: how clean is the separation between the front-end and the back-end?
* **Clarity**: does the README clearly and concisely explains the problem and solution? Are technical tradeoffs explained?
* **Correctness**: does the application do what was asked? If there is anything missing, does the README explain why it is missing?
* **Code quality**: is the code simple, easy to understand, and maintainable?  Are there any code smells or other red flags? Does object-oriented code follows principles such as the single responsibility principle? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
* **Security**: are there any obvious vulnerability?
* **Testing**: how thorough are the automated tests? Will they be difficult to change if the requirements of the application were to change? Are there some unit and some integration tests?
	* We're not looking for full coverage (given time constraint) but just trying to get a feel for your testing skills.
* **UX**: is the web interface understandable and pleasing to use? Is the API intuitive?
* **Technical choices**: do choices of libraries, databases, architecture etc. seem appropriate for the chosen application?

Bonus point (those items are optional):

* **Scalability**: will technical choices scale well? If not, is there a discussion of those choices in the README?
* **Production-readiness**: does the code include monitoring? logging? proper error handling?

## Doubts

Send your questions directly to [ben@fastwork.co](mailto:ben@fastwork.co) and cc to [burin@fastwork.co](mailto:burin@fastwork.co).