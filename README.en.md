# CV

## Basic Information

| key     | value                                   |
| ------- | --------------------------------------- |
| Name    | Yoshiki Masubuchi              |
| Blog    | [Blog](https://yoshixj.com)           |
| Quiita  | [Quita](https://qiita.com/yoshixj)      |
| Twitter | [@yoshixj](https://twitter.com/yoshixj) |

## Summary
I've been working with Rails and Vue.js for a long time.
I can develop from the front end to the back end of the web.
My specialty is Rails for the backend and Nuxt.js for the frontend, but I also have experience using Go and React, so it doesn't take much time to catch up.

# Working History

| date | v1                                  | v2                                             |
| ---- | ----------------------------------- | ---------------------------------------------- |
| 2015 | Entered Chuo University, Faculty of Science and Engineering, Department of Information Engineering |                                                |
| 2016 | FOURDIGIT, inc (part-time job)     |  Markup Engineer                         |
| 2017 | Div, inc  (part-time job)         | Programing teacher                                       |
| 2018 | NiCOLA, inc (part-time job)      | Rails Engineer                               |
| 2019 | Graduated Chuo University      | I was working on elliptic cryptography.        |
| 2019 | NiCOLA, inc  (full-time employee)          | Tech Lead                                      |
| 2020 | Doorkel, inc (subcontractor)         | Rails Engineer    |
| 2021 | Seibii, inc (subcontractor)       | Ruby Engineer|

## NiCOLA, inc (2018/08 - Current)

### Shopify application deverlopment
- Next.js x Typescript / Firestore

### D2C business support software development

- backend: Golang x gqlgen
- frontend: Nuxt x Typescript x graphql-codegenerator
- infra: GAE/CloudTasks/Firestore/CloudSQL/ShopifyAPI

We were developing tools to support our own D2C business.

- Build a system to aggregate data using Shopify's API and analyze it using BigQuery and Redash.
- Development of a Saas-like service for storing order data


We chose gqlgen as our FW because we wanted to use GraphQL, develop schema first and type safe. The service was released internally and then closed because updates could not keep up with changes in the business.

### Takeaway App  (2018/08-2019/08)

- Rails5/GAE/GCS/CloudSQL/Docker/Swagger/Stripe/Vue

We've developed an API using Rails.
We used JWT for authentication.
This was a new development projects, and I did all the design work.
I also used fast_jsonapi as a serializer for the API.

We also used GAE's flexible environment to host Rails on GCP.
We used Stripe for payments, so we implemented the transactions carefully.

We also had a little help from an outsourcer to implement the admin screen.
We implemented the admin panel as an SPA in Vue.js, taking into account changes in specifications and the fact that SEO is not necessary.
We used Vuex to manage the data.


### Gourmet App Development　(2018/08-2019/01)

- I was developing an app that allows you to stock your favourite restaurants.
- heroku/Rails4/postgres/PostGis/Docker/Redash/Swagger

I was developing an API using Rails.
I was using PostGis to handle location information.
I also re-indexed database to improve performance.
I also replaced the development environment with docker-compose.
In the middle of the project, I became the only engineer in the company, so I became a kind of development manager. I also improved communication with our outsourced iOS developers who work remotely.

As for the failures

- I couldn't get the existing adapter gem for postgis to work, so I wrote a sql directly in the model
- The initial design of the Database was not good. (bad relationships, status management, etc.)

## Doorkel (2020/02 - 現在)

### Development of marketing support tools for educational institutions

- backend: Rails (REST API + Graphql)
- front: Nuxt (一部 typescript)
- infra: heroku/ZoomAPI

We use Rails for the backend and Nuxt for the frontend.
With vue3, we've also taken the lead in introducing the composition API to some of our services.
We recommend using typescript, composition API, and graphql-code-generator to make your Frontend development experience good.
Putting the business into the data model in the Saas product was challenging.
By using platuml and other tools, we were able to align the members' perceptions.

## Div (2017/07 - 2018/08)


- I was a mentor for a programming teacher teaching RubyOnRails.
- I also became the mentor with the highest monthly student rating.
- I was also in charge of the office and managing the class.
- Environment: slack/github/jobcan

div Inc. was an environment where I was able to learn the basics of communication as a mentor.
As a mentor, I learned the basics of communication and how to make the students feel comfortable when they come to the classroom.
The most important thing I gained was the ability to listen. Working with a wide range of people, I feel that it is very important to always be willing to listen to what they think.
It was also a company where I could experience first-hand the culture of a growing venture company.

## FOURDIGIT (2016/08 - 2017/08)

### Homepage development

- HTML/CSS/JS
- photoshop, illustrator
- subversion/mamp/chatwork

I worked there for about a year on a part-time basis.
I worked for a large real estate company and did a lot of markup work for their medium to large scale website.
We didn't use the most advanced technology like vue, react at that time, and sometimes we had to change the same pattern in multiple places, and sometimes we had to replace the code in dozens of HTML/CSS files at once.


# Language Experience

- Ruby
- Go
- GAS
- マークアップ
- javascript, typescript
- plat uml
- 日本語
  - ネイティブ
- 英語
  - 開発に関する英語ドキュメントを読める程度

### Experience of using frameworks and platforms

- Ruby
  - Ruby on Rails
  - middleman
- Go
  - [99designs/gqlgen](https://github.com/99designs/gqlgen)
  - [go-chi/chi](https://github.com/go-chi/chi)
  - [volatiletech/sqlboiler](https://github.com/volatiletech/sqlboiler)
  - dbmate
  - goa
- typescript, javascript

  - Puppeteer
  - React / Next.js
  - Vue / Nuxt.js

- Docker
- Haroku
- GCP
  - GAE/GCS/CloudSQL/CloudTasks/CloudScheduler/CloudFunction
- Firebase
  - Authentication/CloudFunctions/CloudStorage/Hosting/Fireastore

### Others

- github
- slack/chatwork
- Asana
- Redash

