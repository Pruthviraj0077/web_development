Selectors
CSS selectors allow us to choose specific elements and apply styles to them. Suppose we want to add a custom style to only a specific tag(s). There, we can make use of CSS selectors.

There are different types of CSS selectors, which are as follows:

Universal Selector
Element Selector
Id Selector
Class Selector
Group Selector
Let's look into these selectors one by one.

Universal Selector
Universal selector represented by * targets all the HTML elements on the page.

The syntax of Universal Selector is as follows:

* {
    property: value;
}

Consider the code snippet:

<html>
<head>
    <style>
        * {
            color: purple;
            text-align: center;
        }
    </style>
</head>
<body>
    <p>Welcome to selectors </p>
    <h1>universal selctor</h1>
</body>
</html>



Element Selector (Type Selector)
The element selector selects the target element based on the specific type. Suppose you want to underline all the <p> tags; in this case, the element selector will be the best choice.

The syntax of Element Selector is as follows:

p {
    property: value;
}

A selector can be any HTML tag. Here, we have considered the p tag.

Consider the code snippet:

<html>
<head>
    <title>CSS</title>
    <style>
        p {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>elemental selector</h1>
    <h2>hi there</h2>
    <p>we are learning web develoment</p>
    <p>javascript</p>
    <p>React JS </p>
</body>
</html>



ID Selector
The ID selector targets the elements based on the specific ID. It is written with the hash # character followed by the ID name in the style sheet.

The syntax of ID Selector is as follows:

#ID {
    property: value;
}

Consider the code snippet:

<html>
<head>
    <style>
        #title {
            text-align: center;
            color: red;
        }
    </style>
</head>
<body>
    <h1 id="title">learning css</h1>
    <p>Id selector</p>
</body>
</html>

In the style block, the selector #title will only target the HTML element having an ID of "title".

Consider the output of the above code:


Class Selector
The class selector does the same job as the id selector, a class selector helps group various types of elements. Suppose, we want to give a custom style to a specific group of elements. In this case, the class selector is the best option.

It is written with the period . character followed by the class name in the style sheet.

The syntax of Class Selector is as follows:

.class {
    property: value;
}

Consider the code snippet:

<html>
<head>
    <title>CSS</title>
    <style>
        .red {
            color: red;
        }
    </style>
</head>
<body>
    <p>This is simple p tag</p>
    <p class="red">This p tag has class red</p>
    <p>This is simple p tag</p>
    <p class="red">This p tag has class red</p>
</body>
</html>

In the above code snippet, the color: red will only be applied to the element having class 'red'.



Group Selector
The group selector is used to minimize the code. Commas , are used to separate each selector in a grouping. This reduces the number of lines of code. The code also looks clean.

The syntax of Group Selector is as follows:

div, p, a {
    property: value;
}

Consider the code snippet:

<html>
<head>
    <title>CSS</title>
    <style>
        h1 {
            color: red;
        }
        p, a {
            color: purple;
        }
    </style>
</head>
<body>
    <h1>group selector</h1>
    <p>This is the p tag</p>
    <a href="#">This is the anchor (a) tag</a>
</body>
</html>

In the <style> block, p and a tags are grouped together so that both tags will have the same properties.

Summary:
Universal Selector (*): Target the entire page.
Element Selector: Target a specific element.
ID Selector (#): Target element with a specific ID.
Class Selector (.): Target element(s) with the same class.
Group Selector: Group elements and target them.
With selectors, CSS gives you the precision to style your page exactly how you want—whether it’s one element, a group of them, or even just the first letter of a paragraph.