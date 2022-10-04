# NavigationViewBitmapIconScaleBug

## Steps
1. Change resolution on secondary monitor (e.g., 150%).
2. Open the app on that specific secondary monitor.

**Expected results**: All NavigationView icons display correctly.
Main monitor 200% scale:
![scale200](https://user-images.githubusercontent.com/16784153/193875454-fcf77f5f-d093-4d1b-bda8-f0006b438d28.gif)

Secondary monitor 150% scale:
**Observed results**: All NavigationView bitmap icons are not visible.
![scale150](https://user-images.githubusercontent.com/16784153/193875485-b0667607-2bff-4f41-8c72-30a74466240c.gif)

