a =2
y=3
z=4
a+y
5
a + y * z
14
( x + y ) * y
Traceback (most recent call last):
  File "<pyshell#6>", line 1, in <module>
    ( x + y ) * y
NameError: name 'x' is not defined
(x+y) * z
Traceback (most recent call last):
  File "<pyshell#7>", line 1, in <module>
    (x+y) * z
NameError: name 'x' is not defined
40 + 2.23
42.23
float(2.23)
2.23
float(2.34) + int(5)
7.34
"app" + "code"
'appcode'
a,y,z
(2, 3, 4)
a + 1 , y * 2
(3, 6)
y % 2
1
100 ** 2
10000
2 ** 100
1267650600228229401496703205376
2 ** 100000
Traceback (most recent call last):
  File "<pyshell#17>", line 1, in <module>
    2 ** 100000
ValueError: Exceeds the limit (4300 digits) for integer string conversion; use sys.set_int_max_str_digits() to increase the limit
2 ** 1000
10715086071862673209484250490600018105614048117055336074437503883703510511249361224931983788156958581275946729175531468251871452856923140435984577574698574803934567774824230985421074605062371141877954182153046474983581941267398767559165543946077062914571196477686542167660429831652624386837205668069376
2 ** 10000
19950631168807583848837421626835850838234968318861924548520089498529438830221946631919961684036194597899331129423209124271556491349413781117593785932096323957855730046793794526765246551266059895520550086918193311542508608460618104685509074866089624888090489894838009253941633257850621568309473902556912388065225096643874441046759871626985453222868538161694315775629640762836880760732228535091641476183956381458969463899410840960536267821064621427333394036525565649530603142680234969400335934316651459297773279665775606172582031407994198179607378245683762280037302885487251900834464581454650557929601414833921615734588139257095379769119277800826957735674444123062018757836325502728323789270710373802866393031428133241401624195671690574061419654342324638801248856147305207431992259611796250130992860241708340807605932320161268492288496255841312844061536738951487114256315111089745514203313820202931640957596464756010405845841566072044962867016515061920631004186422275908670900574606417856951911456055068251250406007519842261898059237118054444788072906395242548339221982707404473162376760846613033778706039803413197133493654622700563169937455508241780972810983291314403571877524768509857276937926433221599399876886660808368837838027643282775172273657572744784112294389733810861607423253291974813120197604178281965697475898164531258434135959862784130128185406283476649088690521047580882615823961985770122407044330583075869039319604603404973156583208672105913300903752823415539745394397715257455290510212310947321610753474825740775273986348298498340756937955646638621874569499279016572103701364433135817214311791398222983845847334440270964182851005072927748364550578634501100852987812389473928699540834346158807043959118985815145779177143619698728131459483783202081474982171858011389071228250905826817436220577475921417653715687725614904582904992461028630081535583308130101987675856234343538955409175623400844887526162643568648833519463720377293240094456246923254350400678027273837755376406726898636241037491410966718557050759098100246789880178271925953381282421954028302759408448955014676668389697996886241636313376393903373455801407636741877711055384225739499110186468219696581651485130494222369947714763069155468217682876200362777257723781365331611196811280792669481887201298643660768551639860534602297871557517947385246369446923087894265948217008051120322365496288169035739121368338393591756418733850510970271613915439590991598154654417336311656936031122249937969999226781732358023111862644575299135758175008199839236284615249881088960232244362173771618086357015468484058622329792853875623486556440536962622018963571028812361567512543338303270029097668650568557157505516727518899194129711337690149916181315171544007728650573189557450920330185304847113818315407324053319038462084036421763703911550639789000742853672196280903477974533320468368795868580237952218629120080742819551317948157624448298518461509704888027274721574688131594750409732115080498190455803416826949787141316063210686391511681774304792596709376
clear
Traceback (most recent call last):
  File "<pyshell#20>", line 1, in <module>
    clear
NameError: name 'clear' is not defined
result  = 1 / 3.0
result
0.3333333333333333
repr("app")
"'app'"
str("app")
'app'
print("app")
app
1<2
True
2 < 2
False
2 <-2
False
2 <= 2
True
5.0 == 5
True
5.0 != 4.0
True
a,y,z
(2, 3, 4)
a < y < z
True
x < y and y < z
Traceback (most recent call last):
  File "<pyshell#34>", line 1, in <module>
    x < y and y < z
NameError: name 'x' is not defined
a < y and y < z
True
a < y or y < a
True
True
True

1 == 2 < 3
False
import math
math.floor(3.55)
3
math.floor(-3.5)
-4
math.trunc(2.8)
2
math.trunc(2.8)
2
math.trucn(-2.8)
Traceback (most recent call last):
  File "<pyshell#45>", line 1, in <module>
    math.trucn(-2.8)
AttributeError: module 'math' has no attribute 'trucn'. Did you mean: 'trunc'?
math.trunc(-2.8)
-2
999999999999999999999999999999999999999999  + 1
1000000000000000000000000000000000000000000
999999999999999999999999999999999999999999 * 2.1
2.1000000000000003e+42
2 + 1j
(2+1j)
(2 + 1j) * 3
(6+3j)
ocaltal
Traceback (most recent call last):
  File "<pyshell#51>", line 1, in <module>
    ocaltal
NameError: name 'ocaltal' is not defined
0o20
16
0o40
32
32
32
0o1
1

hex
<built-in function hex>
0xff
255
0b1000
8
oct(64)
'0o100'
hex(64)
'0x40'
bin(64)
'0b1000000'
int(3.14)
3
int(64)
64
int("64", 8)
52
int("64", 16)
100
int("10000", 2)
16
x = 1
x << 2
4
#import

import random
random.random()
0.4868926917234283
random.random(1,2,3,4,5)
Traceback (most recent call last):
  File "<pyshell#74>", line 1, in <module>
    random.random(1,2,3,4,5)
TypeError: Random.random() takes no arguments (5 given)
random.random(1,10)
Traceback (most recent call last):
  File "<pyshell#75>", line 1, in <module>
    random.random(1,10)
TypeError: Random.random() takes no arguments (2 given)
random.randint(1,10)
6
l1 = [1,2,3,4,5,6]
random.choice(l1)
4
random.shuffle(l1)
l1
[2, 3, 6, 4, 5, 1]
l1
[2, 3, 6, 4, 5, 1]
0.1  + 0. 1 + 0.4
SyntaxError: invalid syntax
0.1 + 0.1 + 0.4
0.6000000000000001
0.1 + 0.1 + 0.1 - 0.3
5.551115123125783e-17
from decimal import Decimal
Decimal("0.1") + Decimal("0.1") + Decimal("0.1")
Decimal('0.3')
from fractions import Fraction
myFra = Fraction(2,7)
myFra
Fraction(2, 7)


#sets
setone = {1,2,3,4}
setone & {1,3}
{1, 3}












#union, superset, intersection, difference
setone | {1,3}
{1, 2, 3, 4}
setone | {1,3,7}
{1, 2, 3, 4, 7}
setone
{1, 2, 3, 4}
setone - {1,2,3,4}
set()
type({})
<class 'dict'>
type(set())
<class 'set'>
type(true)
Traceback (most recent call last):
  File "<pyshell#109>", line 1, in <module>
    type(true)
NameError: name 'true' is not defined. Did you mean: 'True'?
yes
Traceback (most recent call last):
  File "<pyshell#110>", line 1, in <module>
    yes
NameError: name 'yes' is not defined







type(True)
<class 'bool'>
True === 1
SyntaxError: invalid syntax
True == 1
True
False == 0
True