# simple-gitmoji-committer

A simple CLI tool for adding Gitmoji to commit messages interactively. This tool allows you to search for and select a Gitmoji to add to your commit message, making it quick and easy to improve commit readability and expressiveness.

## Installation

To install `simple-gitmoji-committer`, you can use `npm`:

```bash
npm install -g simple-gitmoji-committer
```

## Usage

1. Stage your changes as usual:

    ```bash
    git add .
    ```

2. Run `simple-gitmoji-committer` to start the interactive prompt:

    ```bash
    simple-gitmoji-committer
    ```

3. Follow the prompts:
   - Select a Gitmoji by typing keywords to search or by scrolling through the options.
   - Enter your commit message.

4. After confirming your message, `simple-gitmoji-committer` will generate a commit with the selected Gitmoji and message.

### Example

```bash
$ git add .
$ simple-gitmoji-committer
? Choose a Gitmoji for this commit: ✨:sparkles: Introduce new features
? Enter your commit message: Add user authentication feature
```

The resulting commit message will look like this:

```
✨ Add user authentication feature
```

## Commands

- **`simple-gitmoji-committer`**: Starts the CLI to select a Gitmoji and enter a commit message.

## Scripts

The following npm scripts are available in the project:

- **`npm run lint`**: Runs Prettier and ESLint to check for code formatting and style issues.
- **`npm run fix`**: Fixes any format and lint issues using Prettier and ESLint.

## License

This project is licensed under the MIT License.
