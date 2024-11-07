# ProphecyCore

**ProphecyCore** is the organization responsible for the development and maintenance of the **Prophecy** project, a tool designed to automate the creation of unit tests (UTs) for Angular applications using Karma and Jasmine, based on classes. The goal is to simplify unit test creation, allowing developers to focus on the logical part of the tests, while the tool takes care of the initial setup and dependency resolution.

## Project Goals

**Prophecy** aims to provide an intelligent solution for unit test creation. Currently, the tool can generate the base unit test for Angular classes, resolving constructor dependencies and allowing the developer to easily add *its* (unit tests). In the long term, the project plans to:

- Expand support for other JavaScript frameworks.
- Include compatibility with testing libraries such as Jest and others.
- Evolve into generating full *its*, increasing test coverage.
- **Support for multiple programming languages**, beyond JavaScript/TypeScript, including popular ones like Python, Java, Ruby, and more.

## Features

- **Automatic Unit Test Generation**: Creates the basic test structure for Angular classes, with constructor dependencies already resolved.
- **VSCode Integration**: Available as an extension for the Visual Studio Code editor, enabling quick generation of test bases directly in the development environment.
- **Future CLI Support**: Transforming the project into a command-line interface (CLI) tool for use outside of VSCode.

## Vision for the Future

In the long term, **Prophecy** aims to become a robust and widely adopted tool for unit test creation, with the goal of simplifying developers' work and increasing test coverage in projects of any scale.

Additionally, the tool is intended to expand its compatibility with other testing libraries, such as Jest, and even other JavaScript frameworks, providing a more flexible and scalable solution.

### Expansion Plans

- **Support for other testing libraries**: Expand compatibility with Jest and other popular testing libraries.
- **Generation of *its***: Develop the ability to automatically generate *its* for tests, increasing coverage and improving test quality.
- **Compatibility with other languages**: In the long run, expand **Prophecy** to support not only JavaScript and TypeScript but also other popular programming languages like Python, Java, Ruby, and more.

## Important Considerations

### 1. Unit Tests: We're Not Skipping Quality!

One of the critiques **Prophecy** may face is that by automating test creation, the quality of the test code could be compromised. However, the goal of **Prophecy** is not to replace the developer's work but to streamline the creation of the basic test structure, ensuring that the developer can focus on the logical part of the tests, maintaining quality.

### 2. Generative AI: Could AI Be Used for This?

Although AI-based tools can generate unit tests, there are scenarios where AI usage is not feasible due to security, confidentiality, or licensing concerns. **Prophecy** does not rely on AI to generate tests. Instead, it uses algorithms to read the code and generate tests in a safe and efficient manner, without needing to send data to external servers.

## How to Contribute

1. Fork the repository.
2. Create a branch for your feature or fix (`git checkout -b feature/new-feature`).
3. Make your modifications and commit (`git commit -am 'Adding new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a Pull Request.

## License

Distributed under the MIT License. See `LICENSE` for more details.

---

**ProphecyCore** – Streamlining the creation of unit tests in an intelligent and scalable way, focusing on developer productivity and code quality!
