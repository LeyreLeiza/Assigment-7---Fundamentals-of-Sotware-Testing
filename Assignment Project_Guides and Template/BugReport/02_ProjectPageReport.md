## Summary (Summarize the bug encountered concisely)

On the GitLab new project page (`https://gitlab.com/projects/new`), the option to create a blank project displays incorrect text. Due to a typo, the label reads **"Create black project"** instead of the correct **"Create blank project"**.

## Steps to reproduce     

1. Log in to GitLab at `https://gitlab.com/users/sign_in` with valid credentials.
2. Navigate to the new project creation page: `https://gitlab.com/projects/new`.
3. Observe the project type selection options displayed on the page.
4. Read the label of the first option card.

## What is the current bug behavior?

The first project type option on the page displays the text: **"Create black project"**

## What is the expected correct behavior?

The label should read: **"Create blank project"**
     
## Relevant logs and/or screenshots

Screenshot: `Image/Bug_Project_create_blank.png` — clearly shows the typo "Create black project" on the project type selection page.
No console errors or backend logs are associated with this bug, it is purely a frontend issue.     

## Possible fixes

The fix is a one-word text change in the frontend source code. Locate the UI string for the blank project option.
Change the text from: "Create black project" to: "Create blank project"

## Whom do you report/ Assign To/ Tags

/label ~bug ~reproduced ~needs-investigation
/cc @project-manager
/assign @frontend-developer

## Priority

**Priority: Minor**

Although this bug does not break any functionality, users can still click the option and create a blank project successfully, the incorrect text is visible to all users on a core navigation page and damages the perceived quality and professionalism of the application. It should be fixed promptly in the next release as a low-effort, high-visibility correction.    
