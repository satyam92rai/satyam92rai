- š Hi, Iām @satyam92rai
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
satyam92rai/satyam92rai is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

#!pip install pyEdgeworthBox
%matplotlib inline
import pyEdgeworthBox as eb
EB=eb.EdgeBox(  u1 = lambda x,y: x**0.6*y**0.4
              , u2 = lambda x,y: x**0.1*y**0.9
              , IE1 = [10,20]
              , IE2 = [20,10])
EB.plot()
