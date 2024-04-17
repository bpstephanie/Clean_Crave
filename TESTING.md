# Testing

## Validator Testing

The Clean Crave site has be throughly tested. All the code has been run through the [W3C html Validator](https://validator.w3.org/) and the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/). Minor errors were found on the home and inspiration pages. After a fix and retest, no errors were returned for both. 

The HTML W3C validator validator results for each page:

Home page:
![W3C Validator Test Results](https://github.com/bpstephanie/Clean_Crave/blob/main/media/W3C-screenshots/html_valid_home.png)

Recipes page:
![W3C Validator Test Results](https://github.com/bpstephanie/Clean_Crave/blob/main/media/W3C-screenshots/html_valid_recipes.png)

Contact page:
![W3C Validator Test Results](https://github.com/bpstephanie/Clean_Crave/blob/main/media/W3C-screenshots/html_valid_contact.png)

Newsletter page:
![W3C Validator Test Results](https://github.com/bpstephanie/Clean_Crave/blob/main/media/W3C-screenshots/html_valid_newsletter.png)

Submitted Enquiry pages:
![W3C Validator Test Results](https://github.com/bpstephanie/Clean_Crave/blob/main/media/W3C-screenshots/html_valid_submittedenquiry.png)

The CSS Validator results are:
![(Jigsaw) Validator Test Results](https://github.com/bpstephanie/Clean_Crave/blob/main/media/W3C-screenshots/css_valid.png)

## Responsiveness Test

The responsive design tests were carried out by [Responsive Design Checker](https://www.responsivedesignchecker.com/) and [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/).

## Browser Compatability

Clean Crave was tested on  Google Chrome, Safair, Mozilla Firefox, Microsoft Edge, iOS and Andriod with no visible issues for the user. [BrowserStack](https://www.browserstack.com/) was used to test functionality, appearance and responsiveness. 

## Known Bugs

### Resolved

During validation of the HTML pages, 4 bugs came up:
  - On the Home page:

  1. I had added a button inside an 'a' tag which is not allowed, therefore I removed the 'a' tag and added a form tag.

  2. I had mistakenly written 'p1' instead of 'p'. I corrected this.

  3. I had used the same id attribute twice, therefore I changed both to a class.

 ![index.html validator testing](https://github.com/bpstephanie/Clean_Crave/blob/main/media/W3C-screenshots/html-home-page-1.png)



  - Recipes page
![recipes.html validator testing](https://github.com/bpstephanie/Clean_Crave/blob/main/media/W3C-screenshots/html-recipe-page-1.png)

1. I had not yet added an alt attribute to my image. I corrected this.

### Unfixed Bugs

 - The data from the form doesn't push anywhere. If I were ever to do a true deployment of this site I would solve this issue.

## Additional Testing

The site was also tested using [Google Lighthouse](https://developers.google.com/web/tools/lighthouse). The results were as follows:

![Google Lighthouse Rating](https://github.com/bpstephanie/Clean_Crave/blob/main/media/lighthouse_rating.png)