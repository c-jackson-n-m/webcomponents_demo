##How to run
Just clone and run

##The idea flow in web components
Create the html markup in a &lt;template&gt; tag --> this will make up the content of our ShadowDOM    
Create another tag, we will use this tag as the host element  
Select this element using JavaScript, and call `createShadowRoot` on it, so that we can get the
*root* element --> this is where we append the ShadowDOM into the page for rendering.  
Select the content of the template we created earlier and append it as a child of the host element.  
Now, the shadow dom will be rendered through the host element
