# COVID-19 ASK A SCIENTIST READ ME
## About the widget

This widget is part of the COVID-19 Ask A Scientist QnA tool developed by the [Federation of American Scientists](www.fas.org), [The Governance Lab at NYU](www.thegovlab.org) and the [New Jersey Office of Innovation](www.innovation.nj.gov). 

See the project website at [covid19.fas.org](www.covid19.fas.org).

## Instructions for adding the AskAScientist widget on your website.

See a live demo on [www.thegovlab.org](www.thegovlab.org).

In order to add the widget to your site, you need to add 2 pieces of code.
1. Copy the code in the tooltip.html file from this repo and add it into the <body> of your page.
2. Copy the code in the script.html file from this repo and add it into the <head> of your page. 

### Other Notes

#### Widget Icon
By default, the widget has a question mark icon. This icon was download from nounproject (svg file is available in the img folder of this repo. You do not need to copy this file). If you prefer to use your own icon, change the absolute URL on line 12 of script.html and add an absolute URL to the icon of your choice. The icon file must be a square of 180px, ideally svg but png/jpg will work too. 

#### Textbox
A small textbox will appear above the widget to describe the widget to the user. In order to make this as non-intrusive as possible for your site, the textbox disappears after 10 seconds or when the users moves the cursor over the box. 
To change the 10 second timer, change the value on line 40 of script.html (default (in ms): 10000).
To change the mouseover behaviour, change the parameter on line 35 of script.html (default: mouseover). 

#### Known Issue
If the the widget appears small in mobile view, make sure that the following line is placed in the <head> section of your code:
<meta name="viewport" content="width=device-width, initial-scale=1">

## Contact Us
For questions or clarifications, please get in touch with us at team@innovation.nj.gov

