# HTML5-Form-Validation

You have probably seen forms on the web that give users messages if the form control has not been filled in correctly; this is known as form validation. Traditionally, form validation been performed using JavaScript (which is beyond the scope of this book). But HTML5 is introducing validation and leaving the work to the browser.Validation helps ensure the user enters information in a form that the server will be able to understand when the form is submitted. Validating the contents of the form before it is sent to the server the helps: 
● Reduce the amount of work the server has to do
● Enables users to see if there are problems with the form faster than if validation were performed on the server.

<form action="http://www.example.com/login/"
      method="post">
  <label for="username">Username:</label>
  <input type="text" name="username"
   required="required" /></title><br />
  <label for="password">Password:</label>
  <input type="password" name="password"
   required="required" />
  <input type="submit" value="Submit" />
</form>
