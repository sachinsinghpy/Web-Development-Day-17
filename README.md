# Web-Development-Day-17
CSS Selector
There are different types of CSS selectors, which are as follows:
Universal Selector
Element Selector
Id Selector
Class Selector
Group Selector
(1.) Universal Selector :
-> Universal selector represented by * targets all the HTML elements on the page.
The syntax of Universal Selector is as follows:
* {
    property: value;
}
(2.) Element Selector :
-> The element selector selects the target element based on the specific type. Suppose you want to underline all the <p> tags; in this case, the element selector will be the best choice.
The syntax of Element Selector is as follows:
p {
    property: value;
}
(3.) ID Selector :
-> The ID selector targets the elements based on the specific ID. It is written with the hash # character followed by the ID name in the style sheet.
The syntax of ID Selector is as follows:
#ID {
    property: value;
}
(4.) Class Selector :
-> The class selector does the same job as the id selector, a class selector helps group various types of elements. Suppose, we want to give a custom style to a specific group of elements. In this case, the class selector is the best option.
It is written with the period . character followed by the class name in the style sheet.
The syntax of Class Selector is as follows:
.class {
    property: value;
}
(5.) Group Selector :
-> The group selector is used to minimize the code. Commas , are used to separate each selector in a grouping. This reduces the number of lines of code. The code also looks clean.
The syntax of Group Selector is as follows:
div, p, a {
    property: value;
}
Summary:
-> Universal Selector (*): Target the entire page.
-> Element Selector: Target a specific element.
-> ID Selector (#): Target element with a specific ID.
-> Class Selector (.): Target element(s) with the same class.
-> Group Selector: Group elements and target them.
