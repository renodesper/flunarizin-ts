## Development Guide

- Fork or clone the project

    ```sh
    git@github.com:renodesper/flunarizin-ts.git
    ```

- Create a meaningful branch

    ```sh
    git checkout -b <your-meaningful-branch>
    ```

    e.g:

    ```sh
    git checkout -b new-payment-provider
    ```

- Create some changes and their tests (unit test, integration test, and other test if any).

- Make sure you format/beautify the code by running

    ```sh
    make format
    ```

- As a reminder, always run the command above before add and commit changes.
    That command will be run in CI Pipeline to verify the format.

- Test your changes

    ```sh
    make test.unit
    ```

- Add, commit, and push the changes to repository

    ```sh
    git add .sh
    git commit -s -m "your meaningful commit message"sh
    git push origin <your-meaningful-branch>
    ```

    For writing commit message, please use [conventionalcommits](https://www.conventionalcommits.org/en/v1.0.0/) as a reference.

- Create a Pull Request (PR). In your PR's description, please explain the goal of the PR and its changes.

- Ask the other contributors to review.

- Once your PR is approved and its pipeline status is green, ask the owner to merge your PR.
