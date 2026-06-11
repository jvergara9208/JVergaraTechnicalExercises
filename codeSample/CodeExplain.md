## The problem being solved

  This project automates the main user flows of the SauceDemo ecommerce site, including login, browsing products, adding items to the cart, and completing
  checkout. The goal is to show how I approach reliable end-to-end testing for flows that are important to the user experience.

  ## Key design decisions

  I used Playwright with TypeScript because it provides strong browser automation support and keeps the code clear and typed. I organized the project with the
  Page Object Model so the tests stay readable and the page-specific logic is easy to maintain. I also centralized test data, used stable `data-test` selectors
  when possible, and added reporting through Playwright HTML reports and Allure.

  ## Any trade-offs considered

  I tried to keep the framework structured without making it overly complex. A larger project might need more layers, helpers, or shared utilities, but for
  this sample I focused on keeping the code easy to understand while still showing patterns that can scale.

  ## Why you selected this example

  I selected this example because it represents the kind of automation work I enjoy building: practical, maintainable, and focused on real user journeys. It
  shows my experience with Playwright, TypeScript, test architecture, reporting, and creating tests that are useful for both local development and CI
  workflows.