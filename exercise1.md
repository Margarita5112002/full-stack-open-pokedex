# Exercise 11.1 Warming up
Think about a hypothetical situation where we have an application being worked on by a team of about 6 people. The application is in active development and will be released soon.

Let us assume that the application is coded with some other language than JavaScript/TypeScript, e.g. in Python, Java, or Ruby. You can freely pick the language. This might even be a language you do not know much yourself.

Write a short text, say 200-300 words, where you answer or discuss some of the points below. You can check the length with https://wordcounter.net/. Save your answer to the file named exercise1.md in the root of the repository that you shall create in exercise 11.2.

The points to discuss:

- Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google.
- What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google!
- Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

# Answers

1. For a java application, checkstyle is the most popular choice for linter. Sonarqube is also a great option as it can be easily integrated with other CI tools. For unit testing, junit is chosen because it is the most popular and documented tool for the job. As well as selenium to write acceptance tests. To build the project, there's multiple options like Apache Ant, Apache Maven and Gradle. Apache Ant is a great choice for simple projects, while Apache Maven and Gradle may be better for more complex projects.
2. Some alternatives are CircleCI, GitLab CI, Atlassian Bamboo, JetBrains TeamCity, Buildkite, Cloud Bees, G2 Deals, Bitrise, Gearset, Buddy, etc.
3. The benefits of a cloud-based environment are ease of setup, container support, reliability and affordability. On the other hand, self-hosted are prefer if if the project needs a special configuration or handles very sensitive information. Assuming that such a small project will no need any special configuration then the most suitable option would be a cloud-base CI/CD environment.