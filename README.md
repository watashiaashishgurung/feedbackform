# Lab: Create Feedback Form for Survey


---

## What You Will Learn

In this lab, you will create a **feedback form** using **React functional components** and manage user input details with the `useState` hook. You will implement event handlers to manage form input changes, validate user inputs, and handle form submissions. Additionally, you will create a **confirmation dialog** using the `confirm` method to verify user details before final submission. Upon successful submission, the form fields will reset, and a thank-you message will be displayed to the user.

This lab provides practical experience building **interactive forms** and handling user input in React applications.

---

## Learning Objectives

After completing this lab, you will be able to:

- Create a form to collect user feedback, including their **name**, **email**, and a **feedback message**.
- Handle form submission, including data validation, to ensure users enter required information (name and feedback).
- Display a **confirmation dialog** showing users the information they entered and prompting them to confirm before final submission.
- Reset the form fields to clear input values after submission and provide users with a clean form for submitting additional feedback.

---

## Prerequisites

Before starting this lab, make sure you have the following:

- Basic knowledge of **HTML**.
- Intermediate knowledge of **JavaScript**.
- Basic knowledge of React, particularly:
  - **Function components**.
  - **useState hook**.
  - **Handling forms** in React.

---

## Steps Overview

1. **Build the Feedback Form**:
   - Create the form structure using HTML and JSX inside your React component.
   - Include fields for **name**, **email**, and **feedback message**.

2. **Manage Form Inputs Using useState**:
   - Use `useState` to manage the values of each form field.
   - Implement **event handlers** to update the state as the user types.

3. **Form Validation**:
   - Validate that the user has provided their **name** and **feedback message** before allowing submission.

4. **Confirmation Dialog**:
   - Use the `confirm` method to prompt the user with their entered details and ask for confirmation before submitting.

5. **Handle Form Submission**:
   - On successful confirmation, display a **thank-you message** and reset the form fields for future submissions.

---

## Conclusion

You have implemented a form to collect user feedback in the given `FeedbackForm` component. The component utilizes React's `useState` hook to manage form data state, including the user's name, email, and feedback.

The `handleChange` function updates the form data state as the user inputs information into the form fields. Upon form submission, the `handleSubmit` function prevents the default form submission behavior, displays a confirmation dialog with the user's details, clears the form fields, and shows a thank-you message upon confirmation.

The form includes input fields for the user's name and email, and a text area for providing feedback. 

This project has provided you with practical experience in building dynamic forms, managing user input in React, and ensuring that user interaction is both seamless and validated. By modularizing the feedback form with React hooks, you have learned how to efficiently handle user input and create interactive forms that can be reused in various scenarios.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
## Live Preview

You can view the live preview of this project on GitHub Pages: [Live Preview](https://watashiaashishgurung.github.io/feedbackform/)

---

## Acknowledgments

- This lab is provided by **CognitiveClass.ai**.
