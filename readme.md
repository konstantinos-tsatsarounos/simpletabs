#SimpleTabs

__CSS tabs like archive folders. Contains two files, a css and the tabs.html witch contains the html snippet.__

__You can use the tabs everywhere, however it isn't javascript powered, you have to any extra tabs by hand in the html file and to the css__

###Example

*I intend to one extra tab:*<br /><br />
**i 'll paste the code under div with id of tab-3:**
`<input id="tab-4" type="radio" name="radio-set" class="tab-selector-4" />`
`<label for="tab-4" class="tab-label-4">Contact us</label>`

*And then...*<br />
**This code after the div with the id content-3 in the content div:**
 `<div class="content-4">`
    `<h2>Example Header 4</h2>`
    `<p>Sugar plum chocolate bar candy chocolate toffee cake danish sweet. Icing jelly beans icing dragee lollipop tiramisu. Liquorice pudding bear claw souffle chupa chups biscuit. Muffin gingerbread powder. Dessert unerdwear.com gummies lemon drops dessert brownie carrot cake gummi bears marzipan. Gummies chupa chups tootsie roll.</p>`
`</div>`

>**For the html, the changes are done**

Then go to tabs.css, go to the:

`.tabs input.tab-selector-1:checked ~ .content .content-1,`
`.tabs input.tab-selector-2:checked ~ .content .content-2,`
`.tabs input.tab-selector-3:checked ~ .content .content-3`

And change it to:

`.tabs input.tab-selector-1:checked ~ .content .content-1,`
`.tabs input.tab-selector-2:checked ~ .content .content-2,`
`.tabs input.tab-selector-3:checked ~ .content .content-3,`
`.tabs input.tab-selector-4:checked ~ .content .content-4,`

####The work is done!

