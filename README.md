Условни оператори


if(){  - всяка стойност в () ще бъде прехвърлена в boolean стойност.Ако стойноста е TRUE принтира нея и следващи else и else if не се четат.

}

else if(){ - добавяне на още стойности , гледа се стойността , ако IF е false.

}


else if (){ -  изнълнява се само когато стойността на else if и if e false.

}

strpos - тази функция показва къде се намира търсената от нас информация , Case sensitive.
stripos - same , case insensitive
str_replace - замества текст в текст
str_replace($needle ,$replace , $haystack)


ПРОМЕНЛИВИ:

създаване : 
$x=2;
$y=3;
$x=10; - презаписване на стойостта . Взима се последната стойност.
Типове данни 
$x=null - пример 
echo getType($x) - показва типа на променливата


Integer - цели числа
double / floating point - десетични числа 
string - текст , обграден в кавички.
boolean - 2 възмоности - true or false 

Прехвърляне на един тип към друг : 
$x = "1948"
$y= (int)$x;  -  по този начин прехвърляме от string към integer.

var_dump($y);   - var_dump показва стойността и типа на променливата.
Ако прехвърляме integer към boolean получаваме false единствено , ако integer е 0. Всеки друг вариант е true(-1,1,10 и тн.) Съшото важи и за floating point числата.



Ако прехвърляме string  към boolean винаги получаваме true , само когато имаме напълно празен стринг получаваме false  


от boolean към int.
true  = int (1)
false = int (0)
от boolean към string 
true = string "1"
false  = string ""



String 
$a = 'gosho'
echo strlen($a); - показва броя на символите в string-a 
\  пред символ го прави възможен за интерпретация пример :
$a = "ivan\" " ;   - ще изведе ivan" като резултат.




$а="ivan" 












