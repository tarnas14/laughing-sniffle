# Webinar React Hooks

Example of rewriting a very simple (one component) App frm `class`ic React to react Hooks.

The application (as visible on branch `master`) is a simple application to store your expense history.
It can be written from scratch in ~45 minutes (as shown [here](https://www.youtube.com/watch?v=8VI3hF6Y6WY))

The webinar recording is available [here in Polish](https://www.facebook.com/events/412768789662341/permalink/417481199191100/), but you can follow the steps on this repo by following tags.
These tags are pretty much commits on branch `tdd-tarnas`, so you can also review it there.

We started with tests:

- tag `test1` - first test to check rendering of the application
- tag `test2` - test if the application correctly takes data from the server
- tag `test3` - test if expenses are correctly represented and sent to server
- tag `hooks` - rewrite the component to hooks and see if it still works

At this point we prove that you `can` achieve the same thing with class and hooks.
But we can go even further beyond.
In the next steps you can see test-driven implementation of `useBalance` hook, which encapsulates the logic of expenses calculation.

- tag `setp1`
- tag `setp2`
- tag `setp3`
- tag `split` - unfortunately when we were preparing we used hooks in the same test file, so we decided to split it for clarity

Comments and PRs welcome!

## Tools

1. [react-testing-library](https://github.com/testing-library/react-testing-library) - testing framework
1. [jest-dom](https://github.com/testing-library/jest-dom) - DOM assertions extensions for Jest
1. [user-event](https://github.com/testing-library/user-event) - helpers for firing user events
1. [react-hooks-testing-library](https://github.com/testing-library/react-hooks-testing-library) - hooks testing library
