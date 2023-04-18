# PPCTEST

1. Indentation is not applied in ppc1 css file
2. Indentation is not applied in ppc2 css file ( line 254 to 266)
3. E-Mail field should input type email not text for validation so not requireds javascript
4. ppc_new line number 64 to 69 should be deleted because there is no css writen insite brackets
5. in footer social-icon target is writen incoreectly it should be target="_black"
6. Master css file is not included in ppc.html file
7. Inline style not good practice(because of specificit its overiting all styling which come from css files) so its should be in css file ( many places line h3, label
8. ppc1.css has stylding in classes (.linkcolors, .mainfonts) not applied in ppc.html file and class name should be(.link_colors or .LinkColors)
9. ppc.html file bas <style> element which not needed because allready css files are linked to the html file so whole body styling should be inside css file
10. all input box sizes is small so its should be atleast double size because lots of empty space available
11. Some of styling is writen in css file but actual element is not avaialble in html file like h2 so it shold be deleted
12. Some styling are repated which souldnt be like in master file font-family: 'times new roman';

Improvements
we can use media quries to make page responsive
we can use proproceser SASS or LESS for reusablity of styling
