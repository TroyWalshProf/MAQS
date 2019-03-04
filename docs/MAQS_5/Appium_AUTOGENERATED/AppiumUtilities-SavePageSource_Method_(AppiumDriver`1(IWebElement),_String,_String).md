# AppiumUtilities.SavePageSource Method (AppiumDriver`1(IWebElement), String, String)
 

**Note: This API is now obsolete.**

To capture Page Source during execution

**Namespace:**&nbsp;<a href="MAQS_5/Appium_AUTOGENERATED/Magenic-Maqs-BaseAppiumTest_Namespace">Magenic.Maqs.BaseAppiumTest</a><br />**Assembly:**&nbsp;Magenic.Maqs.BaseAppiumTest (in Magenic.Maqs.BaseAppiumTest.dll) Version: 5.3.0

## Syntax

**C#**<br />
``` C#
[ObsoleteAttribute("SavePageSource that does not take a AppiumTestObject parameter is deprecated")]
public static string SavePageSource(
	this AppiumDriver<IWebElement> appiumDriver,
	string directory,
	string fileNameWithoutExtension
)
```


#### Parameters
&nbsp;<dl><dt>appiumDriver</dt><dd>Type: AppiumDriver(IWebElement)<br />The AppiumDriver</dd><dt>directory</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />The directory file path</dd><dt>fileNameWithoutExtension</dt><dd>Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">System.String</a><br />Filename without extension</dd></dl>

#### Return Value
Type: <a href="http://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a><br />Path to the log file

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type AppiumDriver(IWebElement). When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="http://msdn.microsoft.com/en-us/library/bb384936.aspx">Extension Methods (Visual Basic)</a> or <a href="http://msdn.microsoft.com/en-us/library/bb383977.aspx">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="MAQS_5/Appium_AUTOGENERATED/AppiumUtilities_Class">AppiumUtilities Class</a><br /><a href="MAQS_5/Appium_AUTOGENERATED/AppiumUtilities-SavePageSource_Method">SavePageSource Overload</a><br /><a href="MAQS_5/Appium_AUTOGENERATED/Magenic-Maqs-BaseAppiumTest_Namespace">Magenic.Maqs.BaseAppiumTest Namespace</a><br />