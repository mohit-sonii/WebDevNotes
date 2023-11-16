<strong>Box Model</strong><br>
It is a fundamental concept in Web development  that describes how elements on a web page are structured
and how their dimensions are calculated.<br><br>

<strong>Box Model Components</strong>:- <br>

content area:- It is the field where you content rests.<br>
Padding :-  It is the space between border and your content<br>
Border:-  It is the surrounding of padding. you can say border is boundary <br>
Margin:- The space outside the border, creating a gap between the element and its surrounding elements.<br>
<br><br>

<strong>Padding, Border and margin are applied to 4 sides i.e top,bottom,left and right.</strong>

Total Width Calculation of the box: Given Width + Left Padding + Right Padding + Left Border + Right Border
+ Left Margin + Right Margin
<br>
Total Height Calculation of the box: Given Height + Top Padding + Bottom Padding + Top Border + Bottom Border
+ Top Margin + Bottom Margin
<br>

<strong>Background color of any element shall not considered as margin color
<br> you will see changes when you check and run code</strong>
<br>
<br>
!important <br>
<strong>margin-collapse</strong>
<br>Did you notice that I gave margins to both classes but consider or try to understand what i am trying to say:
<br>
we learnt that if you add a margin property to any element then it will consider as whole means let's say 
<br>margin:25px; <br>
It means top,bottom,left,right margins are all of 25px<br>
if that so then top margin of the 2nd element should display double to the top margin of 1st element.
then why it is not changed?<br>
Here comes the concept of <strong>margin-collapse</strong>
<italic> if the margin of two element is overlapping then the maximum margin will be applied only once.
Like if we have a margin of 25px there on both elements. Both are equal so 25 will be applied only once.
</italic><br>
Refer to my instagram page to learn with examples simultaneously.<br>
<a href="https://instagram.com/developer.mohit"></a>

<strong>box-sizing:border-box;</strong><br><br>
We have given a height of 200px to 1st paragrph<br>
now got to the inspect and then computed ot see the box model. select the p tag and you will see box
model for that element<br>
Now after adding this property, it will become the height of complete box. <br>
means 200-((top border+bottom border)+(top padding+bottom padding)= height of the content.
<br>I hope you got it, to conclude
<br> before adding this property the alone height of content was 200 px and the height of complete box
model will be the adding of <italic>(top,bottom)border&padding + height of content</italic> but after adding
box model property the height of complete box model become the given height and content height will be adjusted
automatically.
<br>
in my example, <br>
Padding :- 25px <italic>becomes 50px when adding both top and bottom</italic><br>
Border:- 2px <italic>becomes 4px when adding both top and bottom</italic><br>
height:-200px;<br>
content height:- 200-50-4 = 146px<br>

-----------------------Let's learn with examples in CSS File




