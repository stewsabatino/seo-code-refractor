# seo-code-refractor
first portfolio - Horiseon 
* Website URL - https://stewsabatino.github.io/seo-code-refractor/
* ![Snippet from Horiseon homepage](./assets/Screen Shot 2021-09-23 at 2.45.57 PM.png)


## Goals
* Refactoring existing code
* Increase accessibility
* Accessible alt attributes
* Headings to fall in sequential order
* Concise and descriptive titles
* Use correct semantic HTML elements
* Push portfolio piece to Github repository 

### Refactoring / readability / Semantics / Alt attributes
* Refactored most divs to not have a sea of divs to semantic HTML elements
* Increased readability 
* Reduced amount of classes and used more semantic elements
* Use descriptive alt tags

```
<section>
            <img src="./assets/images/online-reputation-management.jpg" alt="Person on laptop holding phone" 
            class="float-right" />

            <h2>Online Reputation Management</h2>

            <p>
                The web is full of opinions, and some of these can be negative. Social media allows 
                anyone with an internet connection to say whatever they want about your business. 
                Online Reputation Management gives you the control over what potential customers see 
                when they search for your business.
            </p>

        </section>
```

#### Accessibility 
* Increase accessibility from search engines

```
<head>

    <meta charset="UTF-8" />

    <link rel="stylesheet" href="./assets/css/style.css">

    <title>Horiseon - Home Page</title>

</head>
```

##### Github Repository
* Create a Git hub Repository
* Use Git commands to push code to personal repository

```
git status
git add -A
git commit -m ""
git push origin head
```



