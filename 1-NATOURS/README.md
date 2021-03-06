# Natours Project

![Natours preview](/readme_media/natours_preview.gif)

## Introduction
<p>This is the first project from the course. It introducts SASS, basic + advanced css styling, CSS architecture and much more. In the section "What was learned" there are annotations on the topics learned.</p>

## Images and Gifs

### Navigation
![Navigation gif](/readme_media/navigation.gif)

### Header
![Header image](/readme_media/header.png)

### Section About
![About gif](/readme_media/about.gif)

### Section Features
![Features image](/readme_media/features.png)

### Section Tours
![Tours gif](/readme_media/tours.gif)

### Section Stories
![Stories gif](/readme_media/stories.gif)

### Section Book
![Book image](/readme_media/book.png)

### Footer
![Footer image](/readme_media/footer.png)



## What was learned
<ul>
    <li>Section 1
        <ul>
            <li>Introduction on positioning elements with relative/absolute</li>
            <li>Introduction on animations with keyframes</li>
            <li>Building the header of the project</li>
            <li>Introduction on pseudo elements, like ::after</li>
        </ul>
    </li>
    <li>Section 2
        <ul>
            <li>Details of the steps made by the browser, when a page is loaded</li>
            <li>How css is parsed, the Cascade and Specificity (order and importance of declarations)</li>
            <li>CSS architecture</li>
            <li>Block Element Modifier (BEM) as build method</li>
        </ul>
    </li>
        <li>Section 3
        <ul>
            <li>Introduction to Sass</li>
            <li>Variables and nesting</li>
            <li>Mixins, functions and extensions</li>
            <li>How to install Sass</li>
            <li>Automatically sass compile and live-server</li>
        </ul>
    </li>
        <li>Section 4
        <ul>
            <li>Implemention of 7 to 1 architecture</li>
            <li>How to compile sass</li>
            <li>Auto compile and autoreload, with live-server</li>
        </ul>
    </li>
        </li>
        <li>Section 5
        <ul>
            <li>How to make code more modular with Sass</li>
            <li>Build overlaping components, as hover by</li>
            <li>Styling a section with skewY()</li>
            <li>Style elements, except for the last child</li>
            <li>Center block elements with margin: 0 auto;</li>
            <li>Create a flipping Card
                <ul>
                    <li>Separate card front and card back, positioning on the same place with positioning absolute;, and hiding with backface-visibility: hidden;</li>
                    <li>Smooth animation with transform: rotateY(); and perspective</li>
                    <li>Blending a front image and linear gradient colors (background-blend-mode)</li>
                    <li>Style the card heading manipulating span width (to break line) and linear gradient for background color</li>
                    <li>Fix the padding added on heading, after the manipulation above, with box-decoration-break.</li>
                </ul>
            </li>
            <li>Add a shape to an element (circle shape), with shape-outside: circle(50% at 50% 50%); Note that the element must be floating, with float: ...; It also need dimensions (width and height)</li>
            <li>The property above only determines that the element has the shape. To actually visually look like that shape, you need the clip-path property.</li>
            <li>How to use CSS property "filter" ex: filter: blur(3px) brightness(80%);</li>
            <li>How to add a background video
                <ul>
                    <li>Can obtain videos on coverr.co</li>
                    <li>Add video on html with the tag video, inside the tag insert two source tags, one with mp4 type and one with webm type, each corresponding to the correct video path.</li>
                </ul>
            </li>
            <li>Style when input is invalid with input:focus:invalid</li>
            <li>Effect to move the text inside the input to the bottom of the input box, when input is focused</li>
            <li>Use + and ~ to select sibblings elements</li>
            <li>fixed button for the page navigation</li>
            <li>Checkbox trick to trigger another element when checkbox btn is checked. With &__checkbox:checked ~ &__background. This will style the &__background when btn is checked.</li>
            <li>Use column-count: 2; to divide the text into two columns</li>
            <li>Use id to target an element when hit and anchor button. Ex: < div id="popup"> will be target when < a href="#popup">. It can be styled with #popup:target.</li>
        </ul>
    </li>
</ul>
