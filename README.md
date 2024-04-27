# 345a1

Imagine that you have been asked to design a website called “Freecycling!” including its registration form.

Freecycling! intends to use this website to enable users to sign up for a freecycling network in their local community, where individuals can give away items they no longer need for free.

A combination of usability, visual appeal and accessibility will make sure the visitors get the most out of your site, building the foundation for an exceptional user experience.

The account creation or registration form is a typical part of websites that provide personalized services.

The user experience of the website and such online forms supports the relationship between the service and its audience.

You are tasked with developing their website. It should include a registration form which will allow new members to fill up their details and submit the form. The business will then handle future freecycling initiatives and other member activities. For this assignment, you will have to prototype only:

1. the homepage and
2. the online registration form

You are designing for a high-fidelity prototype therefore, it does not need to be fully functional (i.e.,the prototype does not connect to a database, nor does it actually submit the form field input). Error checking for format of addresses, passwords, mobile number, is out of scope.

---

# **Part 1: Main page**

Design a homepage for Freecycling!. There are no restrictions as to what you can include in the homepage, as long as you stay with the topic of freecycling.

You are NOT required to actually include a functional browsing page, rather, you just need an informative and appealing homepage.

You should also include a navigation bar, a supporting image and a primary call-to action, in this case a button or link for registration.

Make use of the visual design principles discussed in class and take into account the basic accessibility guidelines.

The screenshot in figure 1 shows an example of a website similar to what Freecycling! wants. Your solution should have a similar visual complexity and use Gestalt principles and other Design

principles where appropriate, and this should be described in the report.

Your design should be suitable for a 1920x1080 screen, more specifically you should check that it looks as you intend it with the Google Chrome tool to test a custom screen size as described in Q10 of the Q&A , and that it is readable if it is displayed on a 14 inch screen, a typical business laptop.

Your design does not need to be responsive.

Both the home screen and the form should be useable without scrolling at this resolution. This is

important for both the homepage and the form to showcase the visual design in this exercise.

The organisation has a particular brand colour that they are known for and that they want used in

the website for brand recognition, and this is sent to you via your UPI email.

Your design should use the colour in an appropriate way that ensures the customer aim of brand recognition through that colour. It must be present in multiple html elements in the homepage, and it must adhere to the more specific specifications below.

Because this assignment aims to give you familiarity with foundational web technologies, the

implementation is limited to vanilla Javascript and the stylesheet w3.css and Fontawesome and

necessary google fonts.

Your website has to meet accessibility guidelines including colour contrast.

---

# **Part 2: Registration form**

Design a registration form for a Freecycling! member. The form should be in a modal window that pops up as an overlay on top of the homepage. The modal window only appears if you click the registration button or link from the homepage.

The modal window should also have a close button (usually a button labelled "x") that closes itself and restores the homepage. This can be achieved using a simple JavaScript code. The button or link that you click to trigger the opening of the modal window must have an id of "trigger-modal".

For example:

<a href="#" id="trigger-modal">Register</a>

Your form should have exactly 3 sections with all of the 8 following input fields (each is exactly only 1 input field):

- User Details
  o Given name
  o Surname
  o Username
  o Password
- Addresses
  o Home Address
  o Work Address
- Contacts
  o Mobile Number
  o Email

For the purposes of this assignment, do not add any additional sections or form fields to the registration form which differ from the above specified sections and fields.

For simplicity, your form should keep these three sections within ONE column, with the fields directed towards one common fate. The visual subdivision into the three sections should only use the principle of proximity.

Furthermore we assume that your design team requires that the three sections have the exact div

ids:

- user-details (For example: <div id="user-details">)
- address-details (For example: <div id="address-details">)
- contact-details (For example: <div id="contact-details">)

Remember to use these exact div ids for each section.

Your design team also requires that you enclose the entire form with a div html element with the id "form-ct". Thus, the form contents should be within <div id="form-ct"><form>...</form></div> In general, the HTML should be well-formed. This can be achieved by using some of the free IDEs that check markup.

image was taken from:
https://unsplash.com/photos/green-white-and-brown-textile-NM0RDJceEC0
https://unsplash.com/photos/green-leaf-tree-during-daytime-Z-R0W37bY4M
