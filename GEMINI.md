# Gemini CLI Contributor Guide

This guide provides instructions and prompt examples for using the Gemini CLI (`gemini-cli`) to contribute to the Awesome Zed repository. Following these guidelines will help streamline the process and ensure contributions align with the project's standards.

## Core Principle

All contributions made via the Gemini CLI must follow the workflow outlined in `CONTRIBUTING.md`. This includes creating a new, descriptively named branch for each change, making the change, and pushing that branch for a Pull Request.

Branch names should follow the convention defined in `CONTRIBUTING.md` (`feat/name`, `fix/name`, etc.).

The agent should be instructed to follow this workflow for every request.

## Example Prompts

You can use the following prompts as templates. Be as specific as possible.

### To Add a New Item

Use this prompt to add a new resource. Provide the category, URL, name, and a clear description.

```
Acting as a contributor to the Awesome Zed repository, please add a new item to the list.

1.  Follow the contribution guide by creating a new branch for this change. Name it `feat/add-new-resource-name`.
2.  Add the following item to the "[CATEGORY]" section of the `README.md` file, ensuring it is in the correct alphabetical order and follows the established format:
    - **URL:** [The URL of the resource]
    - **Name:** [The name of the resource]
    - **Description:** [A brief, one-sentence description of the resource.]
3.  Commit the change with a descriptive message and push the new branch to the remote repository.
```

*(Replace `[CATEGORY]`, `[The URL of the resource]`, etc., with the actual details.)*

### To Correct a Broken Link

```
Acting as a contributor to the Awesome Zed repository, please fix a broken link.

1.  Follow the contribution guide by creating a new branch for this change. Name it `fix/correct-link-for-resource-name`.
2.  In the `README.md` file, find the item named "[Old Name of Resource]".
3.  Replace its old URL, `[Old URL]`, with the new, correct URL: `[New URL]`.
4.  Commit the change with the message "fix: Correct link for [Resource Name]" and push the new branch.
```

### To Remove an Item

```
Acting as a contributor to the Awesome Zed repository, please remove an outdated item.

1.  Follow the contribution guide by creating a new branch for this change. Name it `chore/remove-resource-name`.
2.  In the `README.md` file, completely remove the line for the item named "[Name of Resource to Remove]".
3.  Commit the change with the message "chore: Remove outdated [Resource Name] link" and push the new branch.
```
