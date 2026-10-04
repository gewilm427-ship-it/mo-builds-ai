# ApplyPilot

## What is ApplyPilot?

ApplyPilot is a private university application workspace that helps students prepare their applications before submitting them through platforms such as Common App.

Students do the actual writing and decision-making. AI acts as a coach by giving feedback, asking questions, explaining application sections, and suggesting things the student should think about. It should not write the student's application for them.

## Main User Flow

1. A student creates an account or signs in.
2. They choose a unique username.
3. They enter their private application dashboard.
4. They can work on their activities.
5. They can draft and improve their personal essay.
6. They can save application information.
7. They can upload private application files.
8. An AI coach can give feedback on their work.
9. The student reviews everything before transferring their final answers to the real application platform.

## Accounts

Users can sign in with:
- Email and password
- GitHub

Users stay signed in after refreshing the page and can sign out.

Email users can change their password.

## Privacy

Each student's application information is private.

A signed-in user should only be able to access their own application data and files.

Supabase Row-Level Security will enforce these rules.

## Usernames

Every user chooses a unique username after signing in for the first time.

The app displays the username instead of the user's email.

## Application Data

ApplyPilot will save information such as:
- Activities
- Activity descriptions
- Essay drafts
- Application progress

## Files

Students can upload private files connected to their application.

Files will have:
- A file size limit
- Allowed file types
- Rules preventing other users from accessing them

## AI Coach

The AI Coach helps students think about and improve their own work.

It can:
- Give feedback
- Ask useful questions
- Explain confusing application sections
- Point out areas that may need improvement
- Help students review their application

The AI should coach the student rather than write the application for them.