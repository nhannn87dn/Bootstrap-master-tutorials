# jQuery Selectors


## How to use Selectors


|S.No.|Selector|Description|
|:----|:----|:----|
|1)|Name:|It selects all elements that match with the given element name.|
|2)|\#ID:|It selects a single element that matches with the given id.|
|3)|.Class:|It selects all elements that matches with the given class.|
|4)|Universal(*)|It selects all elements available in a DOM.|
|5)|Multiple Elements A,B,C|It selects the combined results of all the specified selectors A,B and C.|


## Different jQuery Selectors


|Selector|Example|Description|
|:----|:----|:----|
|\*|$("*")|It is used to select all elements.|
|\#id|$("#firstname")|It will select the element with id="firstname"|
|.class|$(".primary")|It will select all elements with class="primary"|
|class,.class|$(".primary,.secondary")|It will select all elements with the class "primary" or "secondary"|
|element|$("p")|It will select all p elements.|
|el1,el2,el3|$("h1,div,p")|It will select all h1, div, and p elements.|
|:first|$("p:first")|This will select the first p element|
|:last|$("p:last")|This will select he last p element|
|:even|$("tr:even")|This will select all even tr elements|
|:odd|$("tr:odd")|This will select all odd tr elements|
|:first-child|$("p:first-child")|It will select all p elements that are the first child of their parent|
|:first-of-type|$("p:first-of-type")|It will select all p elements that are the first p element of their parent|
|:last-child|$("p:last-child")|It will select all p elements that are the last child of their parent|
|:last-of-type|$("p:last-of-type")|It will select all p elements that are the last p element of their parent|
|:nth-child(n)|$("p:nth-child(2)")|This will select all p elements that are the 2nd child of their parent|
|:nth-last-child(n)|$("p:nth-last-child(2)")|This will select all p elements that are the 2nd child of their parent, counting from the last child|
|:nth-of-type(n)|$("p:nth-of-type(2)")|It will select all p elements that are the 2nd p element of their parent|
|:nth-last-of-type(n)|$("p:nth-last-of-type(2)")|This will select all p elements that are the 2nd p element of their parent, counting from the last child|
|:only-child|$("p:only-child")|It will select all p elements that are the only child of their parent|
|:only-of-type|$("p:only-of-type")|It will select all p elements that are the only child, of its type, of their parent|
|parent > child|$("div > p")|It will select all p elements that are a direct child of a div element|
|parent descendant|$("div p")|It will select all p elements that are descendants of a div element|
|element + next|$("div + p")|It selects the p element that are next to each div elements|
|element ~ siblings|$("div ~ p")|It selects all p elements that are siblings of a div element|
|:eq(index)|$("ul li:eq(3)")|It will select the fourth element in a list (index starts at 0)|
|:gt(no)|$("ul li:gt(3)")|Select the list elements with an index greater than 3|
|:lt(no)|$("ul li:lt(3)")|Select the list elements with an index less than 3|
|:not(selector)|$("input:not(:empty)")|Select all input elements that are not empty|
|:header|$(":header")|Select all header elements h1, h2 ...|
|:animated|$(":animated")|Select all animated elements|
|:focus|$(":focus")|Select the element that currently has focus|
|:contains(text)|$(":contains('Hello')")|Select all elements which contains the text "Hello"|
|:has(selector)|$("div:has(p)")|Select all div elements that have a p element|
|:empty|$(":empty")|Select all elements that are empty|
|:parent|$(":parent")|Select all elements that are a parent of another element|
|:hidden|$("p:hidden")|Select all hidden p elements|
|:visible|$("table:visible")|Select all visible tables|
|:root|$(":root")|It will select the document's root element|
|:lang(language)|$("p:lang(de)")|Select all p elements with a lang attribute value starting with "de"|
|[attribute]|$("[href]")|Select all elements with a href attribute|
|[attribute=value]|$("[href='default.htm']")|Select all elements with a href attribute value equal to "default.htm"|
|[attribute!=value]|$("[href!='default.htm']")|It will select all elements with a href attribute value not equal to "default.htm"|
|[attribute$=value]|$("[href$='.jpg']")|It will select all elements with a href attribute value ending with ".jpg"|
|[attribute\|=value]|$("[title\|='Tomorrow']")|Select all elements with a title attribute value equal to 'Tomorrow', or starting with 'Tomorrow' followed by a hyphen|
|[attribute^=value]|$("[title^='Tom']")|Select all elements with a title attribute value starting with "Tom"|
|[attribute~=value]|$("[title~='hello']")|Select all elements with a title attribute value containing the specific word "hello"|
|[attribute*=value]|$("[title*='hello']")|Select all elements with a title attribute value containing the word "hello"|
|:input|$(":input")|It will select all input elements|
|:text|$(":text")|It will select all input elements with type="text"|
|:password|$(":password")|It will select all input elements with type="password"|
|:radio|$(":radio")|It will select all input elements with type="radio"|
|:checkbox|$(":checkbox")|Itwill select all input elements with type="checkbox"|
|:submit|$(":submit")|It will select all input elements with type="submit"|
|:reset|$(":reset")|It will select all input elements with type="reset"|
|:button|$(":button")|It will select all input elements with type="button"|
|:image|$(":image")|It will select all input elements with type="image"|
|:file|$(":file")|It will select all input elements with type="file"|
|:enabled|$(":enabled")|Select all enabled input elements|
|:disabled|$(":disabled")|It will select all disabled input elements|
|:selected|$(":selected")|It will select all selected input elements|
|:checked|$(":checked")|It will select all checked input elements|


