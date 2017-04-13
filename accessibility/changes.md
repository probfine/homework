// Your recommended changes go here

## Visual to the UI (CSS, visual elements)
<strong>Color Contrast</strong>
  -Several instances of failed AA 7:1 contrast ratio found. Examples: Dark blue background and h2 text. H2 text is not light enough; Green button on dark blue background fails all levels. Recommend lightening green buttons; Remove button fails contrast. Overall contrast needs to be reassessed to meet 7:1 contrast ratio guidelines.<br>
<strong>Image alt text</strong>
  -Images that are required for the understanding of the page need to have a desrcription. A good example would be the check marks in the second navigation item. These check marks denote that a section is completed. Recommend adding description letting those using a screen reader know that the check boxes mean that section is complete.

## Technical changes: HTML, CSS, Javascript, ARIA attributes
<strong>Headings</strong>
-Make sure that your headings are not too long. This is more of a guideline than a rule, but some screen reader users navigate by headings, and the longer the headings, the longer it takes for them to get to the block of information they are looking for.<br>
<strong>Navigation</strong>
-Overall the navigation on this page can be confusing to those using a screen reader. The largest issue appears when you search for a doctor, medication, etc. There is a lot of information to sift through before the user would get to the information they need to enter. I would recommend ensuring that proper ARIA landmarks are used.<br>
<strong>Updated Content</strong>
-Once a blind/low vision user has clicked to search for a particular item on an item there is no indicator that the list on the left has been updated. Similarly when selecting an item such as Ibuprofen, there is no indication that the area on the right has been updated. I would recommend looking into Live regions to see if that would suffice. If that cannot be done, I would recommend looking into creating a simplified accessible version that strips aways some of the scripting.<br>
## Content
<strong>All Caps</strong>
-Avoid using All caps if possible. Some screen readers, especially older versions, will sometimes have a difficult time reading all caps words. They tend to spell out each letter, which can get tedious and frustrating for those using a screen reader.<br>
<strong>Redundant Links</strong>
-Ensure that there are no redundant links. Every link should be unique and identifiable.
