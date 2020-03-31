# time-preference
Android library module, providing code for a time preference.

Example snippet from `root_preferences.xml`
```
  <uk.co.stevebosman.timepreference.TimePreference
      android:defaultValue="08:00"
      android:key="latest_wakeup_time"
      android:summary="@string/latest_wakeup_time_summary"
      android:title="@string/latest_wakeup_time" />
```

The preference time stored is a string persisted in the format "HH:mm".
