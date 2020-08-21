---
path: "/html_forms"
title: "HTML Forms"
section: "HTML"
order: 2
description: Welcome to Foundations of Design Systems!
---

# HTML Form

An  **HTML form**  is  _a section of a document_  which contains controls such as text fields, password fields, checkboxes, radio buttons, submit button, menus etc.

An HTML form facilitates the user to enter **data that is to be sent to the server** for processing such as name, email address, password, phone number, etc.
### HTML Form Syntax

     <form  action="server url"  method="get|post">
     //input controls e.g. textfield, textarea, radiobutton, button
     </form>

# HTML Form

An  **HTML form**  is  _a section of a document_  which contains controls such as text fields, password fields, checkboxes, radio buttons, submit button, menus etc.

An HTML form facilitates the user to enter data that is to be sent to the server for processing such as name, email address, password, phone number, etc. 

## Why use HTML Form

HTML forms are required if you want to collect some data from of the site visitor.
For example: If a user want to purchase some items on internet, he/she must fill the form such as shipping address and credit/debit card details so that item can be sent to the given address.

## HTML Form Syntax

    1.  <form  action="server url"  method="get|post">
    2.  //input controls e.g. textfield, textarea, radiobutton, button
    3.  </form>

### HTML Form Tags

|Tag|Description|
|--|--|
|`<form>`|It defines an HTML form to enter inputs by the used side.|
|`<input>`|It defines an input control.|
|`<textarea>`|It defines a multi-line input control.|
|`<label>`|It defines a label for an input element.|
|`<fieldset>`|It groups the related element in a form.|
|`<legend>`|It defines a caption for a `<fieldset>` element.|
|`<select>`|It defines a drop-down list.|
|`<optgroup>`|It defines a group of related options in a drop-down list.
|`<option>`|It defines an option in a drop-down list.
|`<button>`|It defines a clickable button.
### HTML 5 Form Tags
|Tag|Description|
|--|--|
|`<datalist>`|It specifies a list of pre-defined options for input control.
|`<keygen>`|It defines a key-pair generator field for forms.
|`<output>`|It defines the result of a calculation.

### HTML elements

 - **`<form>`**
The HTML `<form>` element provide a **document section to take input from user**. It provides various interactive controls for submitting information to web server such as text field, text area, password field, etc.
 - **`<input>`**
The HTML `<input>` element is fundamental form element. It is used to create form fields, to take input from user. We can apply different input filed to gather different information form user.
 - **TextField  Control**
The **type="text"** attribute of input tag creates textfield control also known as **single line textfield control**. The name attribute is optional, but it is required for the server side component such as JSP, ASP, PHP etc.
 - **`<textarea>`**
The `<textarea>` tag in HTML is used to **insert multiple-line text in a form**. The size of `<textarea>` can be specify either using "rows" or "cols" attribute or by CSS.
 - **Label Tag in Form**
It is considered better to have label in form. As it makes the code parser/browser/user friendly.If you click on the label tag, it will **focus on the text control**. To do so, you need to have for attribute in **label tag that must be same as id attribute of input tag**.
 - **Password Field Control**
The password is **not visible to the user** in password field control.
### HTML 5 Elements
 - **Email Field**
  The email field in new in HTML 5. It validates the text for correct email address. You must use @ and . in this field.
 -  **Radio Button Control**
The radio button is used to **select one option from multiple options**. It is used for selection of gender, quiz questions etc.
If you use one name for all the radio buttons, only one radio button can be selected at a time.
Using radio buttons for multiple options, you can only choose a single option at a time.
 - **Checkbox Control**
The checkbox control is used to **check multiple options from given checkboxes**.
 - **Submit button control**
HTML  **`<input type="submit">`**  are used to **add a submit button on web page**. When user clicks on submit button, then form get submit to the server.
 - **`<fieldset>`**
The `<fieldset>` element in HTML is used to **group the related information of a form**. This element is used with `<legend>` element which provide **caption for the grouped elements**.
 
 #### Form Example

    1.  <!DOCTYPE html>
    2.  <html>
    3.  <head>
    4.  <title>Form in HTML</title>
    5.  </head>
    6.  <body>
    7.  <h2>Registration form</h2>
    8.  <form> // **<form> field** 
    9.  <fieldset> 
    10.  <legend>User personal information</legend>
    11.  <label>Enter your full name</label><br>
    12.  <input  type="text"  name="name"><br>
    13.  <label>Enter your email</label><br>
    14.  <input  type="email"  name="email"><br>
    15.  <label>Enter your password</label><br>
    16.  <input  type="password"  name="pass"><br>
    17.  <label>confirm your password</label><br>
    18.  <input  type="password"  name="pass"><br>
    19.  <br><label>Enter your gender</label><br>
    20.  <input  type="radio"  id="gender"  name="gender"  value="male"/>Male <br>
    21.  <input  type="radio"  id="gender"  name="gender"  value="female"/>Female <br/>
    22.  <input  type="radio"  id="gender"  name="gender"  value="others"/>others <br/>
    23.  <br>Enter your Address:<br>
    24.  <textarea></textarea><br>
    25.  <input  type="submit"  value="sign-up">
    26.  </fieldset>
    27.  </form>
    28.  </body>
    29.  </html>

##### OUTPUT
![HTML Form Example](https://static.javatpoint.com/htmlpages/images/html-form-example.png)

##### References 
[https://www.w3.org/TR/html4/interact/forms.html](https://www.w3.org/TR/html4/interact/forms.html)
[https://htmlreference.io/forms/](https://htmlreference.io/forms/)
[https://marksheet.io/html-forms.html](https://marksheet.io/html-forms.html)

