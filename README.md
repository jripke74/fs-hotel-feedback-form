# fs-hotel-feedback-form

In this workshop, you will build a Hotel Feedback Form.

You will practice working with labels, inputs, fieldsets, legends, textareas and buttons.

Step 1
In this workshop, you will practice working with HTML forms by building a Hotel Feedback Form.

Start by adding the <!DOCTYPE html> followed by an html element with a lang attribute of en.

Inside your html element, add a head element.

Step 2
Inside your head element, nest a meta element with the charset attribute set to the value "UTF-8".

Below that meta element, add a title element. The title element's text should be Hotel Feedback Form.

Step 3
To prepare to create some actual content, add a body element below the head element.

Step 4
For the introductory text, you will want to display the main title followed by a short note about leaving feedback.

Inside your body element, add a header element.

Inside the header element, add an h1 element. The h1 element's text should be Hotel Feedback Form.

Below your h1 element, add a p element. The p element's text should be Thank you for staying with us. Please provide feedback on your recent stay.

Step 5
Now, it is time to add the main element which represents the main content of the page.

Step 6
In the previous lecture videos, you learned how to work with the form element like this:

Example Code
<form method="value-goes-here" action="url-goes-here">
  <!-- inputs go inside here -->
</form>
The action attribute is used to specify where the form data should be sent when the form is submitted.

The method attribute is used to specify the HTTP method to use when sending the form data. The most common methods are GET and POST.

NOTE: You will learn about how HTTP methods work in later modules.

Inside your main element, add a form element with an action attribute set to "https://hotel-feedback.freecodecamp.org" and a method attribute set to "POST".

Step 7
Forms consist of inputs where users can input their data. You can group related inputs together using the fieldset element.

Here is an example of using a fieldset element:

Example Code
<form action="/example-url">
  <fieldset>
  <!-- inputs go inside here-->
  </fieldset>
</form>
Inside your form element, add a fieldset element.

Step 8
When working with fieldset elements, it is common to use a caption to describe the group of inputs. You can use the legend element for this.

Here is an example of using a legend element:

Example Code
<form action="/example-url">
  <fieldset>
    <legend>Personal Information</legend>
    <!-- inputs go inside here-->
  </fieldset>
</form>
Inside your fieldset element, add a legend element with the text Personal Information.
