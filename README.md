# student-mobile-portal

A student portal project for practicing Git and GitHub collaboration.

## Student profile component

`StudentProfile.jsx` is a reusable React function component in the repository root.
It displays a Student Profile heading and three labeled fields:

| Field | Fictional example |
| --- | --- |
| Name | Maria Santos |
| Student ID | 2026-001 |
| Program | BS Information Technology |

The data is defined inside the component for this standalone exercise. All
student details are fictional. Do not replace them with real student records.

## Scope

This Session 10 activity demonstrates Git history, feature branches, pull
requests, and review. It does not require an initialized React app. Opening the
JSX file directly in a browser will not render it; JSX needs a React build setup.

## Integration example

In an existing React project, copy `StudentProfile.jsx` into `src/` beside
`App.jsx`, then import and render it:

```jsx
import StudentProfile from "./StudentProfile.jsx";

function App() {
  return (
    <main>
      <h1>Student Mobile Portal</h1>
      <StudentProfile />
    </main>
  );
}

export default App;
```

Start the existing project's development server using its documented command.
Confirm the heading and all three fictional values shown in the table above.
If the project uses the classic JSX transform, add `import React from "react";`
at the top of JSX files; projects using the automatic JSX transform do not need it.

The integration example is a proactive documentation improvement. It is not
evidence that a classmate has reviewed the pull request.

## Review workflow

Feature branch: `feature/student-profile`.
Target branch: `main`.

Review naming, formatting, the three required fields, and the documentation.
Keep the pull request open for a classmate or instructor to review. Merge only
after receiving the permission and instructor approval required by the activity.
