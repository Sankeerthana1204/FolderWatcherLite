# 🌟 Welcome to FolderWatcherLite!

We're absolutely thrilled you're considering contributing to FolderWatcherLite! Your interest and efforts are what make open-source projects like ours thrive. This document will guide you through the process of contributing, ensuring a smooth and enjoyable experience for everyone involved.

FolderWatcherLite is a lightweight, efficient, and user-friendly tool built with **TypeScript, HTML, and SCSS** to help users monitor file system changes. We believe in collaboration and are excited to see your ideas come to life!

## 🚀 Getting Started

Before you dive in, here are a few steps to get you set up:

1.  **Fork the Repository:**
    Start by forking the `FolderWatcherLite` repository on GitHub. This creates a copy of the project under your GitHub account where you can make your changes.

2.  **Clone Your Fork:**
    Clone your forked repository to your local machine:
    ```bash
    git clone https://github.com/Sankeerthana1204/FolderWatcherLite.git
    cd FolderWatcherLite
    ```

3.  **Install Dependencies:**
    FolderWatcherLite uses npm for package management. Make sure you have Node.js installed, then run:
    ```bash
    npm install
    ```

4.  **Run the Project (Development Mode):**
    To see FolderWatcherLite in action and test your changes, you can usually start a development server. (You might need to adjust this command based on your project's specific build setup, e.g., `npm start` or `npm run dev`).
    ```bash
    npm run dev
    ```

## 🤝 How to Contribute

We welcome all kinds of contributions, big or small! Here's a general workflow:

1.  **Find an Issue or Create One:**
    *   Check our [Issues page](https://github.com/Sankeerthana1204/FolderWatcherLite/issues) for existing tasks. Look for issues labeled `good first issue` if you're new!
    *   If you have a new idea, bug report, or feature request, please open a new issue first to discuss it. This helps prevent duplicate work and ensures your contribution aligns with the project's direction.

2.  **Create a New Branch:**
    Once you've decided what to work on, create a new branch from `main`:
    ```bash
    git checkout main
    git pull origin main # Ensure your main branch is up-to-date
    git checkout -b feature/your-feature-name # For new features
    # Or: git checkout -b bugfix/issue-number # For bug fixes
    ```

3.  **Make Your Changes:**
    *   Implement your changes, keeping our [Coding Style Guidelines](#-coding-style-guidelines) in mind.
    *   **TypeScript:** Write clear, type-safe code.
    *   **HTML:** Ensure semantic and accessible markup.
    *   **SCSS:** Organize your styles and follow BEM or a similar methodology if applicable.
    *   Add or update tests as necessary to cover your changes.

4.  **Test Your Changes:**
    Before submitting, please make sure your changes work as expected and haven't introduced any regressions.
    ```bash
    npm test 
    ```

5.  **Commit Your Changes:**
    Follow our [Commit Message Guidelines](#-commit-message-guidelines) when committing your work.
    ```bash
    git add .
    git commit -m "feat: Add new awesome feature"
    ```

6.  **Push to Your Fork:**
    ```bash
    git push origin feature/your-feature-name
    ```

7.  **Open a Pull Request (PR):**
    *   Go to your forked repository on GitHub and open a new Pull Request.
    *   **Important:** Make sure your PR targets the `main` branch of the original `FolderWatcherLite` repository.
    *   Provide a clear and concise description of your changes in the PR template. Reference any related issues (e.g., `Closes #123`).
    *   Our maintainers will review your PR, provide feedback, and might request changes. Please be patient and responsive!

## ✏️ Coding Style Guidelines

Consistency is key for maintainable code! We strive to follow these guidelines:

*   **TypeScript:**
    *   Adhere to our `tsconfig.json` rules.
    *   Use `const` and `let` appropriately. Avoid `var`.
    *   Write explicit types where possible, but leverage type inference.
    *   Follow common TypeScript best practices for interfaces, types, and classes.
*   **HTML:**
    *   Use semantic HTML5 elements.
    *   Ensure accessibility (ARIA attributes, proper alt text for images, etc.).
    *   Keep markup clean and well-indented.
*   **SCSS:**
    *   Organize styles logically (e.g., by component, feature, or using a methodology like BEM).
    *   Use variables for colors, fonts, and common values.
    *   Avoid overly nested selectors.
    *   Add comments for complex or non-obvious styling.
*   **General:**
    *   We use `ESLint` and `Prettier` to enforce code style automatically. Please ensure your code passes linting checks before submitting. You can run them manually:
        ```bash
        npm run lint
        npm run format
        ```
    *   Keep functions and components small and focused.
    *   Add comments for complex logic, but prefer self-documenting code.

## 📝 Commit Message Guidelines

Clear and consistent commit messages make it easier to understand the project's history and track changes. We follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.

**Format:**

\<type\>(\<scope\>): \<description\>

[optional body]

[optional footer(s)]

**Examples:**

*   `feat: Add file exclusion patterns to watcher`
*   `fix(ui): Correct flickering issue in file list`
*   `docs: Update CONTRIBUTING.md with commit guidelines`
*   `refactor(core): Improve directory scanning performance`
*   `test: Add unit tests for path normalization utility`
*   `chore: Upgrade webpack to version 5`

**Types:**

*   `feat`: A new feature
*   `fix`: A bug fix
*   `docs`: Documentation only changes
*   `style`: Changes that do not affect the meaning of the code (white-space, formatting, missing semicolons, etc.)
*   `refactor`: A code change that neither fixes a bug nor adds a feature
*   `perf`: A code change that improves performance
*   `test`: Adding missing tests or correcting existing tests
*   `build`: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
*   `ci`: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
*   `chore`: Other changes that don't modify src or test files
*   `revert`: Reverts a previous commit

**Scope (Optional):**
The scope provides additional contextual information. It can be anything specifying the place of the commit change. Examples: `ui`, `core`, `watcher`, `config`, `build`, `docs`.

## 💬 Community Guidelines

We're committed to fostering a welcoming and inclusive community. Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) at all times. In short:

*   **Be respectful and kind.**
*   **Be inclusive.**
*   **Assume good intent.**
*   **Give constructive feedback.**
*   **Be patient.**

If you experience or witness any behavior that violates our Code of Conduct, please report it to [folderwatcherlite.maintainers@gmail.com].

## 🙏 Thank You!

Your contributions are invaluable to the success of FolderWatcherLite. We appreciate your time, effort, and dedication to making this project even better.

Happy coding!
