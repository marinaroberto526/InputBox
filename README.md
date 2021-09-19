# InputBox
Global $g_sValue $g_sValue = InputBox("Test", "Enter a number between 1 and 99 : ", "0") MsgBox(4096, "", "%ERRORLEVEL% = "&amp; $g_sValue) Exit($g_sValue)
