Comments
Comments in CSS play a crucial role in improving code readability and maintainability, serving as valuable documentation for developers who review or modify the code in the future.

Comments are ignored by the browser and don't affect the styling or layout.

CSS Comments are enclosed between /* and */.

There are two types of comments in CSS:

Single-line comment
Multi-line comments
Single-line comment:
Single-line comments are contained within one line. They are useful for short annotations.

Syntax
selector {
    /* property: value */
}

For example:

/* This is a single line comment */
p {
    /* color: red */
}

Here, the comment is between /* and */.

Multi-line comments:
Multi-line comments span across multiple lines, making them ideal for detailed explanations or temporarily disabling blocks of code.

Syntax
selector {
    /* property1: value1
    property2: value2
    property3: value3 */
}

These are similar to single-line comments, but this helps to comment large descriptions, notes, etc.

For example:

/* This is a
multi line
comment */
p {
    /* color: red;
    background-color: purple; */
    color: purple;
    background-color: red;
}

Tip: If you are using VS Code, you can use ctrl + / to comment the line.