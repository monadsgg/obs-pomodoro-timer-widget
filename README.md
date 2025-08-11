# obs-pomodoro-timer-widget

Pomodoro timer and session counter for my Youtube study stream

## How to Use the Timer

1. Open OBS.
2. Go to [https://monadsgg.github.io/obs-pomodoro-timer-widget/](https://monadsgg.github.io/obs-pomodoro-timer-widget/).
3. In OBS, click **Add Source** → **Browser** → **Create New** (give it a name and make sure "Make source visible" is checked) → click **OK**.
4. On the website, click the timer you want to use.
5. Customize the timer by modifying the time or session values in the URL.  
   Example:

   focus timer (50 minutes and 4 sessions):  
   `https://monadsgg.github.io/obs-pomodoro-timer-widget/focusTimer.html?time=50&session=4`

   break timer (10 minutes):  
   `https://monadsgg.github.io/obs-pomodoro-timer-widget/breakTimer.html?time=10`

6. Copy the customized URL and paste it into the **URL** input field in OBS.
7. Set the width to `400` and the height to `300`.
8. Check the following boxes:
   - ✅ Shutdown source when not visible
   - ✅ Refresh browser when scene becomes active
9. Click **Refresh cache of current page**.
10. Click **OK**.
