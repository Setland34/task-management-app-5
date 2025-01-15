# Task Management Application

This is a web-based task management application where users can create, update, and delete tasks. The application includes user authentication and authorization.

## Setup Instructions

1. Clone the repository:
2. Navigate to the project directory:
3. Install the required dependencies:
install
4. Start the development server:
5. Open your browser and navigate to `http://localhost:3000` to view the application.

## Running Tests

To run tests, use the following command:
## Building for Production

To create a production build, use the following command:
This will create a `build` directory with the production-ready files.

## Deployment

To deploy the application, follow the instructions provided by your hosting provider. Ensure that you have set up the necessary environment variables for the application to function correctly.

## User Authentication and Authorization

The application includes user authentication and authorization to ensure that only authorized users can access and modify tasks. Follow these steps to set up user authentication and authorization:

1. Register a new user:
   - Navigate to the registration page.
   - Fill in the required information (username and password).
   - Submit the registration form.
2. Log in with an existing user:
   - Navigate to the login page.
   - Enter your username and password.
   - Submit the login form.
3. Log out:
   - Click the logout button to log out of the application.
4. User permissions:
   - Only authenticated users can create, update, and delete tasks.
   - Ensure that you are logged in to access and modify tasks.

## Interactive Rebase with `git rebase -i HEAD~<number_of_commits>`
The `git rebase -i HEAD~<number_of_commits>` command is used to interactively rebase the last `<number_of_commits>` commits.

## Configuring Git to Sign All Commits with a GPG Key
To configure Git to sign all commits with a GPG key by default, use the following command:

## Using `git push --force-with-lease`
The `git push --force-with-lease` command is used to forcefully push changes to a remote repository while ensuring that no one else has pushed changes to the same branch since you last fetched. This is a safer alternative to `git push --force` as it prevents overwriting someone else's work.

### Benefits of `--force-with-lease` over `--force`
- Prevents accidental overwriting of changes made by others.
- Ensures that your local branch is up-to-date with the remote branch before force-pushing.
- Reduces the risk of losing important commits.
