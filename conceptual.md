### Conceptual Exercise

Answer the following questions below:

- What is a JWT?
  JSON web token

- What is the signature portion of the JWT?  What does it do?
  The signature is used to verify that the sender of the JWT is who it says it is and to ensure that the message wasn't changed along the way.

- If a JWT is intercepted, can the attacker see what's inside the payload?
  Yes

- How can you implement authentication with a JWT?  Describe how it works at a high level.
  When users credentials are authenticated, a JWT is created. The JWT is signed using a secret key known only to the server. It's then sent back to the client and the client then stores the JWT securely, usually in local storage, session storage, or a cookie. When the server receives a request with a JWT, it verifies the token's signature using the secret key. 

- Compare and contrast unit, integration and end-to-end tests.
  Unit tests focus on testing individual units of code in isolation, integration tests verify interactions between components, and end-to-end tests ensure that the entire application behaves as expected from the user's perspective.

- What is a mock? What are some things you would mock?
  Mock objects mimic the behavior of real objects but are designed specifically to assist in testing by providing controlled behavior and predictable responses. Some things you may want to mock in your tests are API's, databases, user interfaces, and time and date functions.

- What is continuous integration?
  CI is a development practice that helps that aims to automate the process of integrating code changes from multiple developers into a shared repository frequently.

- What is an environment variable and what are they used for?
  An environment variable is a key-value pair that exists outside of a program and is accessible to all processes running on the system. They are used to influence the behavior of programs and scripts and to configure the operating system and its components.

- What is TDD? What are some benefits and drawbacks?
  TDD stands for Test-Driven Development. Some benefits are improved code quality, faster feedback loop, and increased confidence. Some drawbacks are potentailly becoming over-reliant on tests and neglecting other forms of validation and often having to update tests to keep up with chagnes of the application. 

- What is the value of using JSONSchema for validation?
  JSONSchema provides a powerful mechanism for defining, validating, and documenting JSON data structures.

- What are some ways to decide which code to test?
  You want to focus on testing code that is complex, error-prone, or critical to the application's functionality.
  You also want to prioritize testing for code that is likely to change frequently or undergo refactoring. 

- What does `RETURNING` do in SQL? When would you use it?
  Returning provides a convenient way to retrieve specific values from SQL operations without requiring additional queries or data retrieval steps.

- What are some differences between Web Sockets and HTTP?
  HTTP is well-suited for traditional client-server interactions. Web Sockets offer a more efficient solution for real-time communication between clients and servers.

- Did you prefer using Flask over Express? Why or why not (there is no right
  answer here --- we want to see how you think about technology)?
  I prefer Flask because I understand Python, I like the minimalist design and flexibility in designing applications, and and because of the extensions for tasks such as authentication and database integration.