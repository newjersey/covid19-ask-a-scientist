# COVID-19 Ask a Scientist Project Readme

## About the project

This widget is part of the COVID-19 Ask A Scientist project developed by the [Federation of American Scientists](https://fas.org), [The Governance Lab at NYU](https://thegovlab.org) and the [New Jersey Office of Innovation](https://innovation.nj.gov) and supported by a network of [volunteers](https://covid19.fas.org/l/en/article/jgibm2l09k-about-this-site).

See the project website at [covid19.fas.org](https://covid19.fas.org).

## Who is using the widget?
Please email us at covid19@fas.org if you decide to use the widget so we can add you to this list and also keep you informed with important updates.

Sites using the widget:

- [Ask a Scientist Homepage](https://covid19.fas.org/)
- [Federation of American Scientists](https://fas.org/ncov/)
- [The Governance Lab at New York University](http://thegovlab.org/)

Thanks for your partnership! 

## Instructions for adding the Ask A Scientist widget to your website

In order to add the widget to your site, you need to add 2 pieces of code to each page (or to your entire site code): 
1. Copy the code in the [tooltip.html](https://github.com/newjersey/covid19-ask-a-scientist/blob/master/tooltip.html) file from this repo and add it into the <body> of your page(s).
2. Copy the code in the [script.html](https://github.com/newjersey/covid19-ask-a-scientist/blob/master/script.html) file from this repo and add it into the <head> of your page(s). 
3. See below for additional instructions if the widget does not appear correctly on your mobile site. 

### Widget preview

![Widget Preview](http://newjersey.github.io/covid19-ask-a-scientist/img/widget-preview.png)

You can preview a live demo of the widget [here](https://newjersey.github.io/covid19-ask-a-scientist/preview.html) and [thegovlab.org](https://thegovlab.org). 


### Other Notes


#### Widget Icon
The widget has a question mark icon. This icon is sourced from [Nounproject](https://thenounproject.com/) (the svg file is available in the img folder of this repo).  

Optional: You do not need to copy this file, but you can host it on your own server if you prefer. You can update the pointer in the files accordingly.

#### Textbox
A small textbox will appear above the widget to describe the widget to the user (see screenshot above). In order to make this as non-intrusive as possible for your site, the textbox disappears after 10 seconds or when the users moves the cursor over the box. 
To change the 10 second timer, change the value on line 40 of script.html (default (in ms): 10000).
To change the mouseover behaviour, change the parameter on line 35 of script.html (default: mouseover). 

#### Known Issue
If the the widget appears small in mobile view, make sure that the following line is placed in the <head> section of your code:
`<meta name="viewport" content="width=device-width, initial-scale=1">`

## Contact Us
For questions or clarifications, please get in touch with us at covid19@fas.org.




