# Yogesh Manware

I build agents, APIs, and cloud services. Recent work is in Python on Google Cloud, with Go services beside it and Java and Spring Boot further back.

Start with the six repositories below. Later tables are older public work, forks, and private repositories. Private links open only when you are signed in as the owner.

## Recent work

| Repository | Stack | What it is |
| --- | --- | --- |
| [agentic-hiring-assistant](https://github.com/yogesh-insta/agentic-hiring-assistant) | Python, Google ADK, Vertex AI, Cloud Run, Go, TypeScript | Hiring assistant for small businesses, on Google Cloud. Python and Google ADK agents write a job ad, shortlist candidates, schedule interviews, and onboard a hire. Go serves the API, and TypeScript is the chat UI. |
| [tradey](https://github.com/yogesh-insta/tradey) | Python, IBKR, Telegram | Local-first algorithmic trading monorepo in Python, aimed at IBKR paper trading, with Telegram alerts. |
| [fxtrade](https://github.com/yogesh-insta/fxtrade) | Go, OANDA, Gemini, Cloud Run | Go trading platform for OANDA practice accounts. It runs FX scanners and a standalone Gemini agent for BTC/USD sentiment. |
| [tradex](https://github.com/yogesh-insta/tradex) | Go, Cloud Run, Cloud Scheduler, Gemini | Go analytics on Cloud Run: a portfolio dashboard, NSE stock rotation, ASX ETF monitoring, and an economic calendar that alerts through Telegram. |
| [family-chat-app](https://github.com/yogesh-insta/family-chat-app) | JavaScript, Firebase, Cloud Run, Gemini | Family chat app for four people on Google Cloud. It works offline and installs on the home screen. Firebase stores the chat, Cloud Run hosts a Gemini assistant that answers `@agent` for reminders, chores, and allowances, and Cloud Scheduler sends due reminders. |
| [btc](https://github.com/yogesh-insta/btc) | Go, OANDA | Go daemon for the OANDA practice BTC_USD market. It watches daily candles for a bull pattern and can open weekday long entries. |

## JavaScript, Node, and web

| Repository | Stack | What it is |
| --- | --- | --- |
| [dynamodb](https://github.com/yogesh-insta/dynamodb) | Node.js, DynamoDB | Node.js examples of DynamoDB DocumentClient create, read, update, and delete. Credentials stay in the environment. |
| [testcypress](https://github.com/yogesh-insta/testcypress) | JavaScript, Cypress | Small Cypress suite that checks a local page, including an XHR call, and records a video. |
| [react_amplify](https://github.com/yogesh-insta/react_amplify) | React, AWS Amplify | React demo that uses AWS Amplify to generate a backend and call it from the app. |
| [my-react-app](https://github.com/yogesh-insta/my-react-app) | React, NGINX, Docker, Travis CI | React app served by NGINX, built with Docker Compose, and deployed with Travis CI and AWS Elastic Beanstalk. |
| [my-graphql-project](https://github.com/yogesh-insta/my-graphql-project) | Node.js, GraphQL, Express, Elasticsearch, React | Node.js API with GraphQL, Express, and Elasticsearch, plus a React client. |
| [javascript-util](https://github.com/yogesh-insta/javascript-util) | Node.js, Docker, Redis | Node.js service packaged with Docker and connected to Redis through Docker Compose. |
| [nodejs-bdd](https://github.com/yogesh-insta/nodejs-bdd) | Node.js, Cucumber.js | BDD examples for a REST API, using Node.js, Cucumber.js, and a JSON server as the mock API. |
| [mask-it](https://github.com/yogesh-insta/mask-it) | Node.js | Library that masks selected values in JSON objects and arrays before the data is sent on. |
| [kafka-producer-consumer-batch-processing](https://github.com/yogesh-insta/kafka-producer-consumer-batch-processing) | Node.js, Kafka | Node.js service that consumes a Kafka batch, processes the messages asynchronously, and produces them to another topic. |
| [nodejs-postgres](https://github.com/yogesh-insta/nodejs-postgres) | Node.js, PostgreSQL | Node.js job that reads orders from a CSV and imports each one into Postgres only when that customer already exists. |
| [nodejs-knex-mysql](https://github.com/yogesh-insta/nodejs-knex-mysql) | Node.js, Knex, MySQL, Jest | Node.js CRUD and transactions with Knex, MySQL, and Jest. |
| [codingTestJs](https://github.com/yogesh-insta/codingTestJs) | JavaScript | JavaScript practice for arithmetic series, sorting, searching, arrays, and HackerRank problems. |
| [MEAN1](https://github.com/yogesh-insta/MEAN1) | Express, Mongoose, MongoDB | Express and Mongoose API for books, stored in a local MongoDB database. There is no Angular client in the repo. |
| [magic-ball](https://github.com/yogesh-insta/magic-ball) | Node.js, React | Magic 8 Ball with a Node.js server and a React client. |
| [ember_poc](https://github.com/yogesh-insta/ember_poc) | Ember.js | Ember CLI proof of concept. The app is the default Ember starter named Ipp. |
| [AngTest](https://github.com/yogesh-insta/AngTest) | AngularJS | Small AngularJS experiments for controllers, scope, and messaging between controllers. |
| [SimpleSwagger](https://github.com/yogesh-insta/SimpleSwagger) | JavaScript | Small utility for REST documentation in the style of Swagger. The write-up is a PowerPoint and a `.wrf` file. |
| [exp1](https://github.com/yogesh-insta/exp1) | Express, MongoDB | Express and MongoDB API for the parking-on-rent app. The database address comes from the environment. |
| [rt5](https://github.com/yogesh-insta/rt5) | Angular, TypeScript | Angular client for the parking-on-rent app. It talks to the API with JSON. |
| [Codathon](https://github.com/yogesh-insta/Codathon) | HTML, Node.js, MongoDB | IoT smart-parking demo. The repo has the client, the server, and the device-side code. |
| [TechPreppers](https://github.com/yogesh-insta/TechPreppers) | HTML, JavaScript | Browser demo for an emergency data response. People and the rescue team share alerts, messages, and a map of supplies. |

## Java and Spring

| Repository | Stack | What it is |
| --- | --- | --- |
| [spring-retry](https://github.com/yogesh-insta/spring-retry) | Java, Spring Boot, Spring Retry | Spring Boot tests that retry a failed call with `@Retryable` and with a `RetryTemplate`. |
| [java-util](https://github.com/yogesh-insta/java-util) | Java, Spring Boot, Gradle, Docker, Redis | Spring Boot service built with Gradle, packaged in Docker, and connected to Redis on Minikube. |
| [fraud-detection](https://github.com/yogesh-insta/fraud-detection) | Java, Spring Boot | Spring Boot service that flags card numbers whose transactions on a given date exceed a threshold. |
| [address-book](https://github.com/yogesh-insta/address-book) | Java, Spring Boot | Spring Boot address book. It stores names and phone numbers and can list a unique set of contacts. |
| [spring-boot-cap](https://github.com/yogesh-insta/spring-boot-cap) | Java, Spring Boot, MongoDB, Spring Security | Spring Boot sample with REST, MongoDB, security, and actuator monitoring. |
| [gcd](https://github.com/yogesh-insta/gcd) | Java, Spring, CXF, MyBatis, MySQL | SOAP and REST APIs with Spring, Apache CXF, MyBatis, and MySQL. The SOAP side computes a GCD. |
| [SpringHibernateMySqlDemo](https://github.com/yogesh-insta/SpringHibernateMySqlDemo) | Java, Spring, Hibernate, MySQL | Spring, Hibernate, and MySQL end to end, with a JSP page. |
| [JPADemo](https://github.com/yogesh-insta/JPADemo) | Java, EclipseLink, JPA, MySQL | EclipseLink JPA against MySQL, set up as an Eclipse project. |
| [SprintTest](https://github.com/yogesh-insta/SprintTest) | Java, Spring, Hibernate | Spring learning samples: AOP, basic wiring, duplicate beans, data access, and Hibernate. |
| [RhinoE4XDemo](https://github.com/yogesh-insta/RhinoE4XDemo) | Java, Rhino, E4X | Rhino and E4X reading and editing XML, both through Java's built-in support and Rhino's own library. |
| [portal](https://github.com/yogesh-insta/portal) | Java, JAX-RS, CXF | Java web samples: a JAX-RS file upload and panels for a process summary, notes, and documents. |
| [coding-challenges](https://github.com/yogesh-insta/coding-challenges) | Java | Java solutions for binary search, sorting, an LRU cache, anagrams, and a stack-based word machine. |
| [OCAJP](https://github.com/yogesh-insta/OCAJP) | Java | Java practice for collections, concurrency, sorting, and Codility-style problems such as binary gap. |
| [Insta](https://github.com/yogesh-insta/Insta) | Bash, SQL, Java, Cassandra | Interview-style notes and snippets for shell scripting, SQL, Java concurrency, Raft, and Cassandra. |

## Forks

| Repository | Stack | What it is |
| --- | --- | --- |
| [stock-tracking-application](https://github.com/yogesh-insta/stock-tracking-application) | Java, MySQL | Fork of a Java app that emails users when a stock hits a stop, a target, or unusual volume. |
| [simple-read-rest-api-express-node](https://github.com/yogesh-insta/simple-read-rest-api-express-node) | Node.js, Express | Fork of a tutorial that builds a read-only REST API with Express and Node.js. |
| [angular-tree-control](https://github.com/yogesh-insta/angular-tree-control) | AngularJS | Fork of wix/angular-tree-control, an AngularJS tree component. |

## Private

| Repository | Stack | What it is |
| --- | --- | --- |
| [sprintboot-mongodb-ssl](https://github.com/yogesh-insta/sprintboot-mongodb-ssl) | Java, Spring Boot, MongoDB, Docker | Spring Boot student API with MongoDB over SSL, Swagger, Lombok, and a Docker build. |
| [addressbook1](https://github.com/yogesh-insta/addressbook1) | Java, Spring Boot | Spring Boot address book for names and phone numbers, including a unique contact list. |
| [ts-app](https://github.com/yogesh-insta/ts-app) | TypeScript, Node.js, React, PostgreSQL | API-first TypeScript starter with Node.js and React. A typed client is generated from the API. |
| [apollo-server-exp1](https://github.com/yogesh-insta/apollo-server-exp1) | Node.js, Apollo Server, GraphQL | GraphQL experiment on Apollo Server, with ESLint, Flow, and a pinned Node version. |
| [private-kafkaJS-ms](https://github.com/yogesh-insta/private-kafkaJS-ms) | Node.js, KafkaJS, Prometheus | Node.js service that consumes Kafka messages and exposes health and Prometheus endpoints. |
| [kafka-producer](https://github.com/yogesh-insta/kafka-producer) | Node.js, Kafka | Node.js Kafka producer and consumer, with notes for a single-machine multi-broker setup. |
| [demo-kafka-consumer](https://github.com/yogesh-insta/demo-kafka-consumer) | Node.js, KafkaJS | Sample KafkaJS consumer. Connecting requires the broker SSL certificate and key. |
| [demo-kafka-producer](https://github.com/yogesh-insta/demo-kafka-producer) | Node.js, KafkaJS | Sample KafkaJS producer. Connecting requires the broker SSL configuration. |
| [nodejs-best-practices](https://github.com/yogesh-insta/nodejs-best-practices) | Node.js, Mocha, Chai, ESLint | Node.js candidate exercise covering Mocha, Chai, and ESLint. |
| [axios-example](https://github.com/yogesh-insta/axios-example) | Node.js, Axios | Node.js script that uses Axios to POST a sequence of workflow test results. |
| [magic-8-ball](https://github.com/yogesh-insta/magic-8-ball) | Node.js, React | Magic 8 Ball with a Node.js server and a React client. |
| [saaco3](https://github.com/yogesh-insta/saaco3) | AWS | Personal copies of three AWS Solutions Architect Associate (SAA-C03) cheat-sheet articles. |
| [test2](https://github.com/yogesh-insta/test2) | — | Empty placeholder repository. |
