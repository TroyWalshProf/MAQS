# SoftAssert.FailTestIfAssertFailed Method()
 

Fail test if there were one or more failures

**Namespace:**&nbsp;<a href="MAQS_5/BaseTest_AUTOGENERATED/Magenic-Maqs-BaseTest_Namespace">Magenic.Maqs.BaseTest</a><br />**Assembly:**&nbsp;Magenic.Maqs.BaseTest (in Magenic.Maqs.BaseTest.dll) Version: 5.3.0

## Syntax

**C#**<br />
``` C#
public void FailTestIfAssertFailed()
```


## Examples

**C#**<br />
``` C#
/// <summary>
/// Verify soft asserts capture VSUnit assert failures
/// </summary>
[TestMethod]
[TestCategory(TestCategories.Utilities)]
[ExpectedException(typeof(AggregateException))]
public void CapturesVSAssertFail()
{
    SoftAssert softAssert = new SoftAssert(new FileLogger(LoggingConfig.GetLogDirectory(), "UnitTests.SoftAssertUnitTests.RespectVSFailsFails"));
    softAssert.Assert(() => Assert.AreEqual("a", "b"));

    softAssert.FailTestIfAssertFailed();
}
```

**C#**<br />
``` C#
/// <summary>
/// Verify soft asserts capture Nunit assert failures
/// </summary>
[TestMethod]
[TestCategory(TestCategories.Utilities)]
[ExpectedException(typeof(AggregateException))]
public void CapturesNUnitAssertFail()
{
    SoftAssert softAssert = new SoftAssert(new FileLogger(LoggingConfig.GetLogDirectory(), "UnitTests.SoftAssertUnitTests.RespectNUnitFails"));
    softAssert.Assert(() => NUnit.Framework.Assert.AreEqual("a", "b"));

    softAssert.FailTestIfAssertFailed();
}
```


## See Also


#### Reference
<a href="MAQS_5/BaseTest_AUTOGENERATED/SoftAssert_Class">SoftAssert Class</a><br /><a href="MAQS_5/BaseTest_AUTOGENERATED/SoftAssert-FailTestIfAssertFailed_Method">FailTestIfAssertFailed Overload</a><br /><a href="MAQS_5/BaseTest_AUTOGENERATED/Magenic-Maqs-BaseTest_Namespace">Magenic.Maqs.BaseTest Namespace</a><br />