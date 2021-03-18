# Forms

in HTML we had `<input>`, `<textarea>`, `<select>`. they maintain their own state and update it based on user input

in reract its kept in a muteable state that is kept in the state property of components.
it can only be updated with `setState()`

the most basic way to use forms in react is referred to uncontrolled form inputs.

1. instant input validation: we can give the user instant feedback without having to wait for them to submit the form (e.g. if their password is not complex enough)

2. instant input formatting: we can add proper separators to currency inputs, or grouping to phone numbers on the fly

3. conditionally disable form submission: we can enable the submit button after certain criteria are met (e.g. the user consented to the terms and conditions)

4. dynamically generate new inputs: we can add additional inputs to a form based on the user’s previous input (e.g. adding details of additional people on a hotel booking)
