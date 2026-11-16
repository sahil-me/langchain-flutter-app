<!---
Copyright 2026 Sahíl Sharma. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

# Contribute to Langchain Flutter App

Everyone is welcome to contribute, and we value every contribution. Code contributions are not the only way to support the project. Improving Flutter UI components, state management, LangChain agent reasoning loops, tool integrations, prompt templates, API communication, performance, architecture, security, testing, or documentation are all valuable ways to contribute to **Langchain Flutter App**.

This project was developed as part of the exploration into combining cross-platform Flutter client applications with powerful LangChain/LangGraph agent architectures and Gemini models. Contributions that improve the user experience, agent reliability, maintainability, and practical application of generative AI mobile/desktop apps are especially welcome.

If you find this project helpful, consider sharing it with others, referencing it in your blogs or projects, discussing it on social platforms, or simply giving the repository a ⭐️ to support the project and the community.

**However you choose to contribute, please be mindful and respect our [Code of Conduct](https://github.com/sahil-me/langchain-flutter-app/blob/main/CODE_OF_CONDUCT.md).**

## Ways to contribute

There are several ways you can contribute to **Langchain Flutter App**.

- **Flutter UI & Component Design:** Improve chat interfaces, responsive layouts, message bubbles, loading states, and overall mobile/desktop user experience.
- **LangChain & Agent Workflows:** Enhance agent reasoning loops, prompt templates, memory management, and multi-agent coordination.
- **Tool-Calling Integration:** Add, test, or refine custom LangChain tools (such as database lookups, product searches, web scrapers, or API connectors).
- **State Management & Architecture:** Optimize state management patterns, dependency injection, and data flow across screens and services.
- **Dart & API Services:** Improve HTTP/WebSocket clients, JSON serialization, error handling, and asynchronous data streams.
- **Gemini Model Integration:** Improve model configuration, structured outputs, instruction following, and response parsing.
- **Performance Optimization:** Improve app rendering speed, widget rebuild efficiency, memory usage, and network request caching.
- **Security & Credential Handling:** Help ensure safe handling of API keys, environment configuration, and local storage.
- **Testing:** Add or improve unit tests for Dart services, widget tests for Flutter UI, and integration tests for agent workflows.
- **Documentation:** Improve the README, setup instructions, architecture documentation, widget guides, and contribution instructions.

> All contributions are valuable to the project and its learning community. 🥰

## Submitting a bug-related issue or feature request

Feel free to open an issue when you encounter a bug or have an idea for improving **Langchain Flutter App**. Include relevant error logs, reproduction steps, Flutter/Dart SDK versions, device/emulator details, or API configuration information when appropriate.

Please check the existing issues before creating a new one. This helps avoid duplicate reports and makes it easier to track existing problems.

### Did you find a bug?

**Langchain Flutter App** becomes more reliable through community feedback, issue reporting, testing, and meaningful contributions.

Before reporting an issue, please make sure the bug has not already been reported under the repository's **Issues** section.

When submitting a bug report, please include the following information:
- Your operating system and development environment (e.g., Windows, macOS, Linux).
- Flutter version (`flutter --version`) and Dart version.
- Device, emulator, or browser target (iOS, Android, Windows, Web, macOS).
- Steps to reproduce the issue.
- A short description of the expected behavior and what actually happened.
- Relevant error messages, stack traces, or console logs.
- The affected component, such as the chat UI widget, LangChain agent executor, API service, or state controller.
- Screenshots or screen recordings, if applicable.
- Any other information that may help reproduce or understand the issue.

Please do not include **API keys**, **passwords**, **authentication tokens**, **service-account credentials**, `.env` **files**, or other **sensitive information** in an issue.

### Do you want a new feature?

If there is a new feature you'd like to see in **Langchain Flutter App**, please open an issue and describe:

1. **Motivation**

   Explain the problem, limitation, or use case that the feature would address.

2. **Feature Description**

   Describe the proposed feature and how you would expect it to work from a user perspective.

3. **LangChain & AI Integration**

   If the feature affects AI capabilities, explain how it should influence agent prompts, tool definitions, model selection, or response parsing.

4. **Flutter UI & Architecture**

   If the feature affects the frontend or service layer, describe the expected changes to widgets, state providers, or data models.

5. **Implementation Details**

   If you have an implementation idea, architecture suggestion, or code snippet, feel free to include it.

6. **Additional References**

   If the feature is inspired by an external project, paper, design, or technical reference, please include the relevant link.

A clear and well-written feature request makes it easier to evaluate and discuss the proposal.

## Do you want to improve Flutter UI and user experience?

The Flutter frontend provides the interactive interface for users to converse with the LangChain agent.

You can contribute by:

- Designing cleaner, more intuitive chat bubbles and input toolbars.
- Improving accessibility, responsiveness across screen sizes, and dark/light theme support.
- Enhancing smooth scrolling, auto-scroll behaviors, and markdown rendering for agent messages.
- Adding feedback indicators for tool execution (e.g., "Searching catalog...", "Processing order...").
- Optimizing widget rebuild performance during active streaming responses.

When modifying AI workflows, ensure that outputs remain clean, well-formatted, and aligned with project constraints (such as avoiding stray quotes or markdown formatting in raw outputs).

## Do you want to improve LangChain and agent logic?

Agents drive the intelligence and tool orchestration of the application.

You can contribute by:

- Refining system prompts and few-shot examples for better instruction following.
- Adding new specialized tools or improving existing tool execution error handling.
- Optimizing conversation history and memory management for long chat sessions.
- Enhancing structured output parsing to reliably map agent responses to Flutter UI models.

## Do you want to improve testing and reliability?

Testing ensures the application remains stable and easy to maintain.

You can contribute by:

- Adding widget tests for interactive UI components.
- Adding unit tests for Dart services, state managers, and tool handlers.
- Testing error recovery when API calls fail or rate limits are hit.
- Improving test coverage and documentation.

## Do you want to improve documentation?

We're always looking for improvements that make Langchain Flutter App clearer and easier to understand.

You can contribute by:

- Fixing typos or grammatical errors.
- Improving the `README` and setup guides.
- Documenting the app architecture, folder structure, and state management flow.
- Adding examples of custom tool creation and agent configuration.

Documentation contributions are especially appreciated when they help new contributors understand the project, set up their environment, and get started safely.

## Fixing outstanding issues

If you notice an existing issue and have a fix in mind, feel free to **[start contributing](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)** and open a Pull Request.

### Making code changes

<details>
<summary><strong>Step-by-step contribution workflow</strong></summary>

#### 1. Fork the repository

Go to the [Langchain Flutter App repository](https://github.com/sahil-me/langchain-flutter-app) on GitHub and click the **Fork** button.

#### 2. Clone your forked repository

Replace `<username>` with your GitHub username.

```bash
git clone https://github.com/<username>/langchain-flutter-app.git
```

Navigate into the project directory:

```bash
cd langchain-flutter-app
```

#### 3. Create a new branch

Create a separate branch for your feature or bug fix.

```bash
git checkout -b feature/your-feature-name
```

For a bug fix, you can use a name such as:

```bash
git checkout -b fix/issue-description
```

#### 4. Ensure Flutter and Dart SDKs are installed

Verify your Flutter installation:

```bash
flutter doctor
```

Make sure you are on a compatible Flutter SDK version supporting your target platforms.

#### 5. Install dependencies

Fetch the required Dart and Flutter packages:

```bash
flutter pub get
```

#### 6. Configure environment variables

If the application requires API keys (such as Gemini or backend endpoints), configure your local environment variables or configuration files according to the project's instructions.

> Never commit API keys, tokens, `.env` files, or secrets to the repository.

#### 7. Run the application locally

Launch the Flutter application on your preferred target device or emulator:

```bash
flutter run
```

Verify that the app compiles and launches successfully before making or testing changes.

#### 8. Make your changes

- Develop the feature or fix the issue.
- Follow the existing project structure, naming conventions, and lint rules (`analysis_options.yaml`).
- Keep changes focused and maintainable.
- Avoid unrelated modifications.
- Test your changes thoroughly across relevant targets.

#### 9. Run tests

Run existing tests to ensure no regressions were introduced:

```bash
flutter test
```

Verify that the application behaves as intended and that outputs are handled gracefully.

#### 10. Commit your changes

From the repository root, review the files you have changed and stage only the intended changes.

```bash
git status
git add <file-or-directory>
git commit -m "Describe your change"
```

Avoid committing local configuration files, build artifacts, or unrelated modifications.

#### 11. Push to your fork

```bash
git push origin feature/your-feature-name
```

Replace the branch name if you used a different one.

#### 12. Create a Pull Request

Open your fork on GitHub and create a Pull Request targeting the original **Langchain Flutter App** repository.

In your Pull Request description:

- Explain what you changed.
- Reference any related issue.
- Describe UI changes or agent behavior updates.
- Include screenshots, logs, or test results when appropriate.

#### 13. Address feedback

If maintainers leave comments or request changes, address the feedback and push the required updates to your branch.

Thank you for taking the time to review and improve the project!

</details>

## Contribution Guidelines

To keep the project maintainable and welcoming:

- Keep Pull Requests focused on a single feature, fix, or improvement.
- Avoid unnecessary changes to unrelated files.
- Follow existing Dart/Flutter style guidelines and linting rules.
- Test changes locally before submitting a Pull Request.
- Keep API keys and sensitive configuration out of the repository.
- Provide clear commit messages and Pull Request descriptions.
- Be respectful and constructive when reviewing or discussing contributions.

## I want to become a maintainer of the project. How do I get there?

**Langchain Flutter App** is a learning and demonstration project focused on integrating cross-platform Flutter clients with LangChain agent architectures and generative AI models.

Contributors interested in improving UI components, agent reasoning, tool integrations, state management, testing, documentation, and architecture are welcome.

If you are interested in contributing at a deeper level, consistently submitting meaningful improvements, reviewing Pull Requests, improving documentation, or helping maintain the project, feel free to get involved and collaborate.

Thank you for contributing to **Langchain Flutter App**! 🚀
