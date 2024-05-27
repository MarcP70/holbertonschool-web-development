 Project: HTML, advanced

### Concepts

_For this project, we expect you to look at these concepts:_

* [Some pointers about HTML](/concepts/834)
* [HTML - elements of a web page](/concepts/835)
* [HTML Foundations](/concepts/836)
* [HTML - Semantic sectioning elements](/concepts/837)
* [HTML Semantic Elements](/concepts/838)
* [HTML Validation](/concepts/839)

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1f4cd63ecc3a8c03b0f4309b74aca179e225aabf.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d781f8d244ea882e1e43d747936c78f5fc18952d0948827fa23a15ad2ae699a5)

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/04a83a0e813e4ae602915c0d844e5c2ba05602f4.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=de09573ed7e54959e24ffe330cc2626b32d0e025a25774c3b5185a12a6ccff12)

Resources
---------

**Read or watch**:

* [Learn to Code HTML & CSS](/rltoken/D6o845Dj6bWanYggYGQK4A "Learn to Code HTML & CSS") (_until “Creating Lists” included_)
* [Introduction to HTML](/rltoken/odwyiWUlo7nyK3UR6FUEdg "Introduction to HTML")
* [MDN](/rltoken/STnL1M-mwzCvnzHtG21XGQ "MDN")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](/rltoken/tk1bYe9n6YmcEsF-gwOgMA "explain to anyone"), **without the help of Google**:

### General

* What is HTML
* How to create an HTML page from a wireframe
* What is a markup language
* What is the DOM
* What is an element / tag
* What is an attribute
* What the purpose of each HTML tag

Requirements
------------

### General

* All your files should end with a new line
* A `README.md` file, at the root of the folder of the project is mandatory
* You are **not allowed** to install, import or use external libraries. This website must be build with only HTML/CSS/JavaScript. No NodeJS, React, VueJS, Bootstrap, etc.
* Your code should be W3C compliant and validate with [W3C-Validator](/rltoken/czWaAX6ZYwSLoR3bh2Qiqg "W3C-Validator")

Tasks
-----

### 0\. README and objectives!

mandatory

In this and coming projects, you will implement from scratch a webpage from a designer file.

For this first project, you will focus on the HTML structure only - **no CSS, no style - just pure HTML semantic.**

This designer file will be available on [Figma](/rltoken/ChJbK90Un6oS2A6ozdyTQA "Figma") \- feel free to create an account to access the final result here:

* [Page in Figma](/rltoken/lhaBvvfXnyGKs9bRxokWtQ "Page in Figma")
* [fig file](/rltoken/BOC4LSHhGgn-RudlXjuUKg "fig file")

And “Duplicate to your Drafts” to have access to all design details.

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2cc84615c5ba9dfbc6af9869528798da0fe84a96dcae236e61b23f3102b44790)

Important notes with Figma:

* if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](/rltoken/76O2REi_XN8esxhm9fZg9w "source-sans-pro") and [Spin-Cycle-OT](/rltoken/tIZuYvssJ291nB0BWUl-Tw "Spin-Cycle-OT")
* some values are in float - feel free to round them

For this task, please write an amazing `README.md`

**Repo:**

* GitHub repository: `holbertonschool-web-development`
* Directory: `html_advanced`
* File: `README.md`

Help

×

#### Students who are done with "0. README and objectives!"

**0/2** pts

### 1\. Header

mandatory

Let’s start at the top: **the header**

Here is the wireframe of it:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/f08f357fc2c894d821a29b7f907f26089ec68d86.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=dcf6f65403e7919cc1a83b8687a06932ec00e9e63006dfbdc9df64569a5e5525)

* Create the HTML skeleton (`html`, `head`, `body`, etc.)

* In the body, add a `header` tag
* Inside this `header`:
    * Add a link element with an image inside
    * Add a block of 3 link elements

**Repo:**

* GitHub repository: `holbertonschool-web-development`
* Directory: `html_advanced`
* File: `index.html`

Help

×

#### Students who are done with "1. Header"

**0/5** pts

### 2\. Banner

mandatory

Now, the banner inside the `header`:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/d3f0dba16af368a681919fb44306fadfb2499b54.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=dd2efeaa5a3ffd6a6022454feb53ff624eae9ee1eba5f8e9005038727dec4440)

Inside the `header`, add a `section` element inside.

In this `section` element, add:

* A block containing:
    * A heading tag (level 1, don’t forget to use the correct heading value)
    * A text element
    * A button tag
* Another block containing:
    * Another heading tag (level 2, be careful about which one you are using)
    * A block containing 4 blocks - each block containing:
        * An image
        * A heading tag (level 3)
        * A text

Under the `header` add a `main` element

**Repo:**

* GitHub repository: `holbertonschool-web-development`
* Directory: `html_advanced`
* File: `index.html`

Help

×

#### Students who are done with "2. Banner"

**0/11** pts

### 3\. Quote

mandatory

Under the banner, we will add the quote block:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2024/4/e898eac85272d52f5528ea81678000045a37017a.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=931744bc421c8abb39352aedfcab7217ba0e1c3e21b129c8745187a397f24373)

The quote section is inside the `main`:

* Create a new `section` for the quote
* Inside, add a block containing:
    * An image
    * Another block with inside:
        * A blockquote tag
        * A text tag for the quote author
        * Another text

**Repo:**

* GitHub repository: `holbertonschool-web-development`
* Directory: `html_advanced`
* File: `index.html`

Help

×

#### Students who are done with "3. Quote"

**0/7** pts

### 4\. Videos

mandatory

Let’s now add the videos list:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/a5712ac70330c6812c6aee2bf21efe7ac53d1397.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=cfd5a21181c1dd4d6202f631542937143ea8de84532bcf9e1a5f754876af7cdd)

New `section` containing:

* A heading tag (level 1)
* A block containing the 4 video blocks - each of them are composed with:
    * An image
    * A heading (level 2)
    * A text
    * Add a block for the author information:
        * An image
        * A heading (level 3)
    * A block for the rating:
        * A block of images (one star = one image)
        * A text

**Repo:**

* GitHub repository: `holbertonschool-web-development`
* Directory: `html_advanced`
* File: `index.html`

Help

×

#### Students who are done with "4. Videos"

**0/12** pts

### 5\. Membership

mandatory

The Membership section is similar to the videos list:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1ddf18bc6d89725de2fde4881e8990fae6d89628.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f4b425a6276f3c09c5c173a1abcfd982bddd34f2af59b9437666c1b7e339b568)

After the videos list section, add a new `section` containing:

* A heading (level 1)
* A block containing 4 block items - each block containing:
    * An image
    * A heading (level 2)
    * A text
* A button

**Repo:**

* GitHub repository: `holbertonschool-web-development`
* Directory: `html_advanced`
* File: `index.html`

Help

×

#### Students who are done with "5. Membership"

**0/5** pts

### 6\. FAQ

mandatory

The FAQ section is ending the page before the footer:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/e4b2806abe9edc126fa0d4155aaf5d7e7da479e4.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2539398cde0440f328881595874bf55744832e34de3da17a1f4f7f5fa3d0609d)

Add a `section` for the FAQ containing:

* A heading (level 1)
* A block that contains 2 “row blocks”
* Each “row block” contains 2 “item blocks”
* Each “item block” is composed of:
    * A heading (level 2)
    * A text

Hint: There is no “row block” tag, “row” is referring to the styling that will be applied in a future project. It just means two “rows” containing two “items” each, also containing their own elements.

**Repo:**

* GitHub repository: `holbertonschool-web-development`
* Directory: `html_advanced`
* File: `index.html`

Help

×

#### Students who are done with "6. FAQ"

**0/5** pts

### 7\. Footer

mandatory

And… the footer!

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/7224527ac842981b3b387cd9d713b4a1b912a487.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240524%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240524T154047Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2d38daba876a9f4e290c67c87401d0d5577029ce4f4858cd19a3b1689fb930c3)

After the last `section`, outside of the `main`, add a `footer`:

* A block (used later for centering the footer content), inside this block:
    * Another block with:
        * An image
        * Another block containing:
            * 3 Images with link
    * A text

And… that’s it for the moment - the result should not be shiny, don’t worry, CSS is coming…

**Repo:**

* GitHub repository: `holbertonschool-web-development`
* Directory: `html_advanced`
* File: `index.html`

Help

×

#### Students who are done with "7. Footer"

**0/5** pts
