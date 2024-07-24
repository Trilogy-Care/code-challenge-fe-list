# Trilogy Care Front End Code Task

### High level summary:
- Using the following API endpoint, create a VueJS app that renders a filterable list of employees.
- We're looking at your ability to componentise the design to enable reusability and a well thought out set of components.
- Submit your solution via zip file, don't create a PR.

Endpoint: https://66a03156b132e2c136003838.mockapi.io/api/v1/users

Design: https://www.figma.com/design/H7LIvDMo7vTCBgTUiov9ID/Front-End-Test-Task?node-id=0-1&m=dev&t=pxkmPzvcyg3dimKI-1

### Functionality expected:
- Search (input box) to filter the list of employees based on name or job_title
- Show the total of filtered employees
- Mobile responsivess as per the designs
- Use tailwinds css for styles (colours correspond to default tailwinds colours)

### Bonus points:
- The filter is applied by query params (in the URL)

### Example JSON object of an employee list item:

{
    "createdAt": "2024-07-23T06:58:39.383Z",
    "name": "Jodi Schmitt",
    "avatar": "https://cloudflare-ipfs.com/ipfs/Qmd3W5DuhgHirLHGVixi6V76LhCkZUz6pnFt5AJBiyvHye/avatar/673.jpg",
    "phone": "(574) 541-1697",
    "job_title": "Future Research Representative",
    "tags": [
      "sky",
      "earth"
    ],
    "id": "1"
  }



