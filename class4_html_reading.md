# This is my reading from CODE-102 class 4 on HTML

This is reading from the book HTML&CSS by Jon Duckett

## Chapter 18 - Process and Design

Every website should be designed for the target audience.

- Target Audience: Individuals
    - Age Range?
    - Gender Specific?
    - What Country do your visitors live in?
    - Urban / Rural?
    - Avg Income?
    - Level of Education?
    - Marital or Family Status?
    - Etc

- Target Audience: Companies
    - What is the size of company or relevant dept?
    - What is the position of the people in the company that use your site?
    - For themselves or someone else?
    - How large is their budget?

***Why Are People Visiting Your Site?***
***What Are Your Visitors Trying to Achieve?***

- Your content and design should be influenced by the goals of your users.
- Two Basic Categories of questions to ask:
    1. Underlying Motivators of Visitors
    1. Specific Goals of Visitors
- Type 1, Key Motivators:
    - Entertainment, to achieve a specific need?
    - If a goal, is it personal or professional?
    - Is time on this site for something essential or luxury?
- Type 2, Specific Goals:
    - What kind of information do they want/need
    - Are they already familiar with the service or product or do they need to be introduced?
    - Is it time sensitive informaition?
    - Do they need to contact you?

***What Information Your Visitors Need?***

- You know who is coming to your site and why, now you need to work out what information they need so they can achieve their goals quick and effectively.

***How Often People Will Visit Your Site***

- How often will you need to update your site based on its frequency of traffic, the type of product you are selling / promoting. And how frequently you are updating your products and services.
    - once a site is built it can take a lot of time and resources updating it frequently.
    - Set a schedule based on the frequency of visits / how often you update the products / services / information of your site.

***Site Maps***

A site map is a diagram of the pages that will be used to structure the site. 

- Card Sorting - a technique used to decide what informaiton should go on each page.

    - Place each piece of information that a visitor might need to know on a separate piece of paper and then organize the related information into groups.
    - Each group relates to a page and on larger sites, the pages can in turn be grouped together to create different sections of the website.
    - Usually begins with a homepage
    - If big website, each section might require its own section homepage, ex. online shops have section homepages for each type of product

***WireFrames***

A wireframe is a simple sketch of the key information that needs to go on each page of a site.

    - Do not include: styling elements
    - Focus purly on the information needed on each page and a visual hierarchy
    - Make design easier because you know the flow of information
    - It can be helpful to show the wireframe to a client before showing them a design.
    - It can ensure the site has all the funtions and information it needs to offer.

    [Online Wireframe Tools](http://gomockingbird.com)
    [Another option](http://lovelycharts.com)

***Getting Your Message Across***

Organizing and prioritizing information on a page helps users understand its importance and what order to read it in.

- Content
    - Online Newspapers are a great example of a website where the information on each page is widely different
    - Types of elements:
    - Masthead or logo
    - Links to navigate site
    - Links to other content
    - Login or membership info
    - Copyright info
    - Ability for users to comment
    - Etc
- Prioritizing
    - Using Visual Hierarchy to help users focus on key messages that will draw people's attention.
    - Most web users do not read the entire page but skim to find information.
    - Use **size**, **color**, **style** to make it easier to read your page.
    - Visual contrast between the items being displayed will help make things easier to read and navigating the site or page easier.
- Organizing
    - Grouping together related content into *blocks* or *chunks* makes the page look simpler and easier to read
    - A big picture understanding should be easy for users to grasp simply by navigating to the page
    - Using a *similar* visual style for certain elements (buttons/links) users will learn to associate that style with a particular type of content

***Grouping and Similarity***

Repetition of similar color, size, orientation, texture, font, or shape, suggests that matching elements have similar importance or meaning.

- Consistency - between headings, links, titles, etc.
- Headings - tells the user whether or not the content of the grouping is relevant to the. It also helps users of screen readers, as users often have the option to hear the headings on the page.

Items to consider:

- Proximity
- Closure
- Continuance
- White Space
- Color
- Borders

***Designing Navigation***

Good navigation tends to follow the below principles:

- Concise
- Clear
- Selective
- Context
- Interactive
- Consistent

## Chapter 17 - HTML5 Layout

- What is HTML5 About?
    - Introducing a new set of elements that help define the structure of a page.
    - They let you divide up the parts of a page in a logical manner
    - The point: so that web page authors can use them to help describe the structure of the page.
    - The new elements provide cleaner code (compared with using multiple `<div>` elements).

- Layout Elements:
    - Header or `<header>`
    - Footer or `<footer>`
    - Navigation or `<nav>` - used to contain major navigational blocks
    - Article or `<article>` - a container for any section of a page that could stand alone and potentially be syndicated.
    - Aside or `<Aside>` - two purposes, when inside an `<article>` it should contain information that is related to the article but not essential to its overall meaning. Ex pullquote or glossary. When outside of an `<article>` it acts as a container for content that is related to the entire page. Ex, links to other sections, a serach box, tweets, etc.
    - Sections or `<section>` - groups related content together, and typically each section would have its own heading. It may contain several distinct `<article>` elements taht have a common theme or purpose. Alternatively if you had a long article the `<section>` could be used to split up the article into two separate sections.
    - Heading Groups or `<hgroup>` - to group together a set of one or more `<h1>` through `<h6>` elements so they are treated as one heading.
    - Figures or `<figure>` which should include a `<figcaption>` - it can be used to coantain any content that is referenced from the main flow of an article. It should not be for something integral to the page.
    - Sectioning Elements or `<div>` - other elements not to be used except for their specific purpose mentioned. Where there is no suitable element to group a set of elements, the `<div>` element will be used. Ex, as a wrapper for an entire page.

- Understanding Older Browsers
    - To help older browsers, you should include the line of CSS whcih states which new elements should be rendered as block-level elements.
    - Older browsers that don't understand HTML5 will automatically render elements as inline elements.

## Chapter 8 - Extra Markup

- Doctypes - tells browsers which version of HTML you are using
- `<!-- This is how to leave a comments within your code -->`
- id and class attributes - allow you to identify particular elements
- `<div>` and `<span>` - all you to group block-level and inline elements together
- `<iframes>` - cut windows into your web pages through which other pages can be displayed.
- `<meta>` - allows you to supply a search engine all kinds of information about your web page.
- Escape Characters are used to include special characters in your pages. A few examples are below:
    - `&copy;` - copyright symbol
    - `&reg;` - registered trademark
    - '&trade;` - trademark
    
    
[<== Back to Readme](README.md)