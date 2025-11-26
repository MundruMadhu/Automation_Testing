Alert:
Alert is a small message box it may be also used for warning purpose. once alert comes we compulsorly handle it otherwise it will throw UnHandleAlertException.

Types of Alerts:
There are three types of alerts
1.Simple Alert : It has Only one button OK Button
2.Confirmation Alert : It has Two buttons OK and Cancel Button
3.Prompt Alert : It has Two buttons and One Input Box.

Methods for handling the alerts:
accept()  : accept() will accept the alert It means it clicks On OK Button.
dismiss() : dismiss() will dismiss the alert It means it clicks on Cancel Button.
getText() : getText() will return alert message
sendKeys(): sendKeys() will enters some text in alert input box

Exceptions:
NoAlertIsPresentException : We Will get this exception, if you are trying to switch the alert which is not present.
UnHandleAlertException : We will get this exception, if you are trying to access the webelement which is present behind the alert.




