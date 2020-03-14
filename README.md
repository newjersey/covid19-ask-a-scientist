# COVID-19 Ask a Scientist Project Readme

## About the project

The [COVID-19 Ask A Scientist project](https://covid19.fas.org) was developed by the [Federation of American Scientists](https://fas.org), [The Governance Lab at NYU](https://thegovlab.org) and the [New Jersey Office of Innovation](https://innovation.nj.gov) and supported by a network of [volunteers](https://covid19.fas.org/l/en/article/jgibm2l09k-about-this-site).

We are making the Ask a Scientist widget available to add to your website via the instructions below.  You can also find text below that you can use to share the site directly with your community and website visitors.

## Who is using the Ask a Scientist widget?
Please email us at covid19@fas.org if you decide to use the widget so we can add you to this list and also keep you informed with important updates. You can open a pull request, but also let us know where to best reach you. 

Sites using the widget:

- [Ask a Scientist Homepage](https://covid19.fas.org/)
- [Federation of American Scientists](https://fas.org/ncov/)
- [The Governance Lab at New York University](http://thegovlab.org/)

Thanks for your partnership! See the bottom of this page for optional language that you can use to highlight this widget on your website. 

## Instructions for adding the widget to your website

In order to add the widget to your site, you need to add 2 pieces of code to each page (or to your entire site code): 
1. Copy the code in the [tooltip.html](https://github.com/newjersey/covid19-ask-a-scientist/blob/master/tooltip.html) file from this repo and add it into the `<body>` of your page(s).
2. Copy the code in the [script.html](https://github.com/newjersey/covid19-ask-a-scientist/blob/master/script.html) file from this repo and add it into the `<head>` of your page(s). 
3. See below for additional instructions if the widget does not appear correctly on your mobile site. 

### Widget preview


You can preview a live demo of the widget [here](https://newjersey.github.io/covid19-ask-a-scientist/preview.html) and [thegovlab.org](https://thegovlab.org). 

A screenshot of the widget when it is closed:

![Widget preview when closed](http://newjersey.github.io/covid19-ask-a-scientist/img/widget-preview.png)

A screenshot of the widget when it is open:

![Widget preview when opened](http://newjersey.github.io/covid19-ask-a-scientist/img/widget-open-preview.png)



### Other Notes

#### Content 
The questions and answer content in the widget will auto-update to match the latest content on the [Ask a Scientist site](https://covid19.fas.org/).

#### Widget Icon
The widget has a question mark icon. This icon is sourced from [Nounproject](https://thenounproject.com/) (the svg file is available in the img folder of this repo).  

Optional: You do not need to copy this file, but you can host it on your own server if you prefer. You can update the pointer in the files accordingly.

#### Textbox
A small textbox will appear above the widget to describe the widget to the user (see screenshot above). In order to make this as non-intrusive as possible for your site, the textbox disappears after 10 seconds or when the users moves the cursor over the box. 
To change the 10 second timer, change the value on line 40 of script.html (default (in ms): 10000).
To change the mouseover behaviour, change the parameter on line 35 of script.html (default: mouseover). 

#### Known Issue
If the the widget appears small in mobile view, make sure that the following line is placed in the `<head>` section of your code:
`<meta name="viewport" content="width=device-width, initial-scale=1">`



## Sharing Ask a Scientist with your community and website visitors

Feel free to use the following optional copy when sharing the widget and service. 

### Announcing the widget on your website

*We have made the COVID-19 "Ask a Scientist" service from the Federation of American Scientists available on our website. You can instantly find answers to your COVID-19 questions by clicking the question mark icon at the bottom of this page. If you don't find the answer you are looking for, click "Ask a scientist your question" to send your question to a network of scientists and journalists who have volunteered to respond. For more information about the project, visit the [COVID-19 Ask a Scientist site](https://covid19.fas.org/).*

### Sharing the service on your website or via email (no widget required)

*The Federation of American Scientists has launched [COVID-19 "Ask a Scientist"](https://covid19.fas.org/) - a service created to answer the public's questions regarding the coronavirus outbreak.*

*Through this service, you can instantly find answers to your COVID-19 questions. If you don't find the answer you are looking for, you can also submit your question to a network of scientists and journalists who have volunteered to respond.*

*All content is sourced from the World Health Organization, the Centers for Disease Control and Prevention, and other reliable sources. Additionally, each answer is researched and edited by a scientist from the FAS network. Visit the [COVID-19 Ask A Scientist site](https://covid19.fas.org/l/en/article/jgibm2l09k-about-this-site) for more information.*

## Contact Us
For questions, clarifications, support, and feedback, please get in touch with us at covid19@fas.org.




