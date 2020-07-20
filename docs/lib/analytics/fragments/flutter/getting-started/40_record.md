To record an event, create an `AnalyticsEvent` and call `Amplify.Analytics.recordEvent()` to send it:




```java
AnalyticsEvent event = AnalyticsEvent("test");

event.properties.addBoolProperty("boolKey", true);
event.properties.addDoubleProperty("doubleKey", 10.0);
event.properties.addIntProperty("intKey", 10);
event.properties.addStringProperty("stringKey", "stringValue");

Amplify.Analytics.recordEvent(event: event);
```