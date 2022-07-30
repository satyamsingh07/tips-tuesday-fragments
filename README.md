 What is a react fragment?

Fragments are syntax that allow us to add multiple elements to a React component without wrapping them in an extra DOM node.

![image](https://user-images.githubusercontent.com/81974869/181891801-aa26fd5d-5f46-4efb-992f-9bd94278d2fa.png)

Above code snippet gives you a glimpse of a basic react component that doesn't need to be wrapped up in the main component.

However if we have let's say one more p element and try to execute the code:-

![image](https://user-images.githubusercontent.com/81974869/181892015-bd86098c-5d76-4fc2-918b-d56c5928dd7c.png)

The above code throws and error!
 
![image](https://user-images.githubusercontent.com/81974869/181892153-a65e186c-9795-4b5b-82a7-ae9b529c9cfa.png)

In order to render both the elements, we can wrap them inside a div tag 
 
![image](https://user-images.githubusercontent.com/81974869/181892332-7e83ddb1-79dd-4b59-a687-a51868179fd8.png)


This implementation is fine if we're using the parent div tag to style and position our components. However,using divs only as a wrapper increases code nesting and   decreases performance.

This is where the use of fragments makes more sense.
The fragment tag acts only as a conatainer and does not interefere with the code structure at all.

![image](https://user-images.githubusercontent.com/81974869/181892606-a5d1ee13-5853-4e1a-b2d2-e886214efcd8.png)

This helps in mantaining a clean code structure and improves performance

