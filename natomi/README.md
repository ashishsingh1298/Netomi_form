# Netomi_form
Design an HTML page with the following requirements:
● Create a form as shown in the image below. The form needs to be loaded in the iframe.
● The Form will have fields like Name, Email address, Contact number, Country and
State.
● Country and state are drop-down, countries are pre-populated from the JSON via an
API call. If a country is selected, only the states of the selected country should be
populated in the state dropdown. Refer to this JSON for countries and states.
● The form validations can be configured from the parent window in the Iframe as shown
in the picture below:
● Add these validations in the form fields:
○ Name - Length should be between 4-10 characters.
○ Email address - should only support valid email address
○ Contact number - mobile number should be of 10 digits.
○ Country, State, Name - are mandatory fields.
● If all fields are valid, show the success message “All fields are valid” on the parent
window or the error message as shown in the image.
Note that the div with a red border is an iframe and the green colour div is the parent window.
For reference -
Iframe - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe
Send data from iframe -
https://developer.mozilla.org/en-US/docs/Web/API/Window/postMessage