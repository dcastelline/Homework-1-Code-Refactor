# **Horiseon Code Refactor**

Horiseon requested that their website codebase be refactored to follow accessibility standards and to be optimized for search engines.

## **Issues Addressed**

*The **HTML** was reformatted and commented to increase readability.
*The page contained three internal links at the top of the page to take the user to the corresponding section of the page. One of the links was non-functioning and was fixed by adding an **id** attribute.
*Numerous **div** tags were replaced by the appropriate semantic tags


contained a number of non semantic tags, lacked **alt** tags on the images, and not all elements requiring them were assigned a proper **class** or **id** attribute. This should assist with the webpage's accessibility.

The **CSS** was found to be excessively long and redundant and lacked comments. The **CSS** was reformatted to reduce redundancy and comments were added to identify what the code was affecting and to aid with future maintainence or other work.
