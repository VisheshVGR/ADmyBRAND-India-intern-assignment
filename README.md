# Coding Challenge Frontend

### [Problem Statement](https://docs.google.com/document/d/1QAe96x7XARZTE0FBrv2s_TUOCk9xhPHeLBqTvOE6ll4/edit)

### Overview
We recommend you aim to complete the task in a day depending on how extensive your solution is on this task. On completion -  fork and make a PR to this repository https://github.com/ad-my-brand/coding-challenge-frontend. The task will involve you implementing a form using React JS (Next JS) or React Native (For Mobile app developer applicants) Please make sure the code is committed and pushed.

Create a branch from `master`
Create a react web application.
Create a component as a Form Control:
  - The control should accept a label.
  - The control should accept a validation function with a configurable error message.
  - The control can be incorporated inside a `<form>` and the selected option pushed up to the form.
  - The control should fire an event on change.

Use the control you made in the previous step to create a form:
  - Call this `https://jsonplaceholder.typicode.com/users` to populate a list of the users. `name` should be displayed while `id` should be saved as the value in the `form`.
- Integrate embedded maps using Google maps api or any other similar service that you prefer to show the location as listed in the above api
  - Add the required validation with the `Please select a user` error message.
  - Add 2 text fields, one for `title` and one for `body` both with required validation.

On submit of the form create a new post by sending the data to `https://jsonplaceholder.typicode.com/posts`. The request interface will look like:
  ```json
  {
    “title”: “foo”,
    “body”: “bar”,
    “userId”: 1
  }
  ```
Handle the error when any of the HTTP requests fails by displaying an appropriate error message to the user.
Writing unit tests for your component.
  - Writing e2e tests for your form.
When you are finished raise a PR for your changes.



Bonus Points


Make sure the form control you have created is meeting WCAG AA level. (https://www.w3.org/WAI/standards-guidelines/wcag/)


Knowledge of react (nextJS)  is a huge plus
