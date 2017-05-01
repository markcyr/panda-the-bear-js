Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead (hint: use attr()).
$('.profile-image').attr('src','https://placebear.com/g/200/300');

Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.
$('#left-image img').attr('src','https://placebear.com/g/200/300');


Select the heading that says "Panda the Bear" and change it to your own name. (hint: use text())
$('H1.highlight').text('MARK');

Select the heading that says "Employment" and change it to something else. (hint: use a descendant selector)
$("H3 .icon-suitcase").text("MR");

Panda the Bear is lying about their skills! Take the "time travel" skill off the page to satisfy your personal sense of justice. Use your googling and docs-skimming skillz to find a jQuery function that will allow you to remove elements from the DOM. (hint: there are multiple ways of doing this, but the parent() function might be useful when it comes to selecting the right element)
-- $('#time-travel').parent().remove(); --

Change the colour of the body. (hint: use css())
-- $('body').css('background-color', 'purple'); --

Change the colour used by the highlight class.
-- $('.highlight').css('color', 'green'); --

Change the font family of the h1 to 'monospace'.
-- $ ('h1').css('font-family', 'helvetica'); --

Find a way to select the round icons in the sidebar and then change their colour.
-- $('.action-icon-bg').css('background-color', 'red'); --

Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".
-- $ ('#name').attr('placeholder', 'Identify yourself'); --

Change the placeholder attribute of the message field to "state your business".
-- $ ('#message').attr('placeholder', 'state your business'); --

Give the name field a "value" attribute of "your nemesis".
-- $ ('#name').attr('value', 'attribute of "your nemesis'); --

Change the value attribute of the email field to "koalathebear@gmail.com".
-- $ ('#email').attr('value', 'fkoalathebear@gmail.com'); --

Change the value of the submit button on the contact form to "En garde!".
-- $ ('#submit').attr('value', 'En garde!'); --


