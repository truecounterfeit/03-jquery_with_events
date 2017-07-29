#### Single-line Summary
**Today, _ and _ paired together. It took about _**

#### Reflect and summarize on your process for each `TODO` item :  
  1. <!-- TODO: Link our new script file in. -->
  Add articleView script link to index.html
  2. <!-- TODO: Use jQuery to also add the author name as a data-attribute of the newly cloned article. Doing so will allow us to use selectors to target articles, based on who wrote them.-->  
  Added data attribute to newArticle jQuery object targeting this.author
  3. <!-- TODO: Add some coordinated colors to make the blog more distinguished:
           Use an accent color for all links, and remove their underline. -->
  Changed body link color to orange
  4. <!-- TODO: If the select box was changed to an option that has a value, we need to hide all the articles, and then show just the ones that match for the author that was selected. Use an "attribute selector" to find those articles, and fade them in for the reader. -->
  Added hide method to jQuery article object. Added fadeIn method to jQuery object attribute selector concatenation.
  5. <!-- TODO: If the select box was changed to an option that is blank, we should show all the articles, except the one article we are using as a template.-->
  Added not and show methods to jQuery article object to not show template class when no specific author is selected.
  6. <!-- TODO: Just like we do for #author-filter above, we should handle change events on the #category-filter element.
  //       When an option with a value is selected, hide all the articles, then reveal the matches.
  //       When the blank (default) option is selected, show all the articles, except for the template.
  //       Be sure to reset the #author-filter while you are at it!-->
  Added if else statement to the on method which is applied to the category-filter. If: hide method to article object while fadeIn selected category. Else: show article but not template.

#### Checklist (before submitting, fill in each set of square brackets with an 'x')
- [] We have titled the Pull Request similar to our branch name (ex: 'brian-rick').
- [] This PR includes commits from both myself and my partner; e.g. We followed good pair programming practices by switching driver/navigator roles.
- [] There is no extraneous, unrelated code included in this PR.
- [] We have summarized our `TODO:` process above.
