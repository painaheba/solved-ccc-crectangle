Download Link: https://assignmentchef.com/product/solved-ccc-crectangle
<br>
Please design a class CRectangle with 2 CPoint objects. These 2 CPoint objects denotes the points ot the top left corner and lower right corner. Please calculate the area of the rectangle.

Notes: Each constructor and destructor of all designed classes should output “*** is called”.

The main function is given as follows：

int main()

{

int a=1, b=1, c=6, d=11;

cout&lt;&lt;“# Define p1 ######”&lt;&lt;endl;

CPoint p1;

cout&lt;&lt;“# Define p2 ######”&lt;&lt;endl;

CPoint p2(10,20);

cout&lt;&lt;“# Define rect1 ######”&lt;&lt;endl;

CRectangle rect1;

cout&lt;&lt;“# Define rect2 ######”&lt;&lt;endl;

CRectangle rect2(p1, p2);

cout&lt;&lt;“# Define rect3 ######”&lt;&lt;endl;

CRectangle rect3(a, b, c, d);

cout&lt;&lt;“# Define rect4 ######”&lt;&lt;endl;

CRectangle rect4(rect2);

cout&lt;&lt;“# Calculate area ######”&lt;&lt;endl;

cout &lt;&lt; “rect1 area:” &lt;&lt; rect1.GetArea() &lt;&lt; endl;

cout &lt;&lt; “rect2 area:” &lt;&lt; rect2.GetArea() &lt;&lt; endl;

cout &lt;&lt; “rect3 area:” &lt;&lt; rect3.GetArea() &lt;&lt; endl;

cout &lt;&lt; “rect4 area:” &lt;&lt; rect4.GetArea() &lt;&lt; endl;

return 0;

}

【样例输出】

# Define p1 ######

CPoint contstructor with default value(0,0) is called.

# Define p2 ######

CPoint contstructor with default value(0,0) is called.

# Define rect1 ######

CPoint contstructor with default value(0,0) is called.

CPoint contstructor with default value(0,0) is called.

CRectangle default contstructor is called.

# Define rect2 ######

CPoint copy contstructor is called.

CPoint copy contstructor is called.

CPoint copy contstructor is called.

CPoint copy contstructor is called.

CRectangle contstructor with (CPoint,CPoint) is called.

# Define rect3 ######

CPoint contstructor with default value(0,0) is called.

CPoint contstructor with default value(0,0) is called.

CRectangle contstructor with (int,int,int,int) is called.

# Define rect4 ######

CPoint copy contstructor is called.

CPoint copy contstructor is called.

CRectangle copy contstructor is called.

# Calculate area ######

rect1 area:0

rect2 area:200

rect3 area:50

rect4 area:200

Answer : Please fill the gap(………) with c++ language code

#include  &lt;iostream&gt;using  namespace  std;//Please  give  the  definition  of  CPoint，CRectangle……………………………………………………………….int  main(){int  a=1,  b=1,  c=6,  d=11;cout&lt;&lt;“#  Define  p1  ######”&lt;&lt;endl;CPoint  p1;cout&lt;&lt;“#  Define  p2  ######”&lt;&lt;endl;CPoint  p2(10,20);cout&lt;&lt;“#  Define  rect1  ######”&lt;&lt;endl;CRectangle  rect1;cout&lt;&lt;“#  Define  rect2  ######”&lt;&lt;endl;CRectangle  rect2(p1,  p2);cout&lt;&lt;“#  Define  rect3  ######”&lt;&lt;endl;CRectangle  rect3(a,  b,  c,  d);cout&lt;&lt;“#  Define  rect4  ######”&lt;&lt;endl;CRectangle  rect4(rect2);cout&lt;&lt;“#  Calculate  area  ######”&lt;&lt;endl;cout  &lt;&lt;  “rect1  area:”  &lt;&lt;  rect1.GetArea()  &lt;&lt;  endl;cout  &lt;&lt;  “rect2  area:”  &lt;&lt;  rect2.GetArea()  &lt;&lt;  endl;cout  &lt;&lt;  “rect3  area:”  &lt;&lt;  rect3.GetArea()  &lt;&lt;  endl;cout  &lt;&lt;  “rect4  area:”  &lt;&lt;  rect4.GetArea()  &lt;&lt;  endl;return  0;}


