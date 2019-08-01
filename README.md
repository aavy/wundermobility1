# wundermobility1

Task: To develop a small web application, which includes a basic user registration, which contains 4 separate steps. 

View 1: Insert personal information
- Firstname, lastname, telephone

View 2: Insert address information
- Address including street, house number, zip code, city

View 3: Insert payment information
- Account owner
- IBAN (doesn’t need to be validated)

When clicking the “next” button, the inserted data should be saved locally in the browser storage and the payment
data should be posted to our external “demo-payment” api with the following configuration:

URL:
https://37f32cl571.execute-api.eu-central-1.amazonaws.com/default/wunderfleet-recruiting-b
ackend-dev-save-payment-data

View 4: Success page

===================================================================================================================

1. Describe possible optimizations for your code.

Reduce the file size of the images being loaded on to the website. 

2. Which things could be done better, than you’ve done it?

I usually create projects on Maven, but I did not have access to the Eclipse Software, hence used a simple structure.

Major changes that I would have implemented: 
  1. Use ReactJS or any other JS framework. 
  2. Implement MVC in the project.
  3. Enhance the styling of the form
  4. Reduce the opacity of the CarPool image in the slider
  5. Include a video in the slider, rather than an Image
  
