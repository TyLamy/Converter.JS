# Calculator.JS

<FORM NAME = "Calculator">
  
<TABLE BORDER = 4>
<TR>
<TD>
<INPUT TYPE = "text"   name = "Input" Size = "16">
<br>
</TD>
</TR>
<TR>
<TD>
<INPUT TYPE = "button" name = "one"   value = "1" onClick = "Calc.Input.value += '1'">
<INPUT TYPE = "button" name = "two"   value = "2" onCLick = "Calc.Input.value += '2'">
<INPUT TYPE = "button" name = "three" value = "3" onClick = "Calc.Input.value += '3'">
<INPUT TYPE = "button" name = "plus"  value = "+" onClick = "Calc.Input.value += ' + '">
<br>
<INPUT TYPE = "button" name = "four"  value = "4" onClick = "Calc.Input.value += '4'">
<INPUT TYPE = "button" name = "five"  value = "5" onCLick = "Calc.Input.value += '5'">
<INPUT TYPE = "button" name = "six"   value = "6" onClick = "Calc.Input.value += '6'">
<INPUT TYPE = "button" name = "minus" value = "-" onClick = "Calc.Input.value += ' - '">
<br>
<INPUT TYPE = "button" name = "seven" value = "7" onClick = "Calc.Input.value += '7'">
<INPUT TYPE = "button" name = "eight" value = "8" onCLick = "Calc.Input.value += '8'">
<INPUT TYPE = "button" name = "nine"  value = "9" onClick = "Calc.Input.value += '9'">
<INPUT TYPE = "button" name = "times" value = "x" onClick = "Calc.Input.value += ' * '">
<br>
<INPUT TYPE = "button" name = "clear" value = "  c  " onClick = "Calc.Input.value = ''">
<INPUT TYPE = "button" name = "zero"  value = "0" onClick = "Calc.Input.value += '0'">
<INPUT TYPE = "button" name = "enter" value = "=" onClick = "Calc.Input.value = eval(Calc.Input.value)">
<INPUT TYPE = "button" name = "div"   value = "/" onClick = "Calc.Input.value += ' / '">
<br>
</TD>
</TR>
</TABLE>
</FORM>

