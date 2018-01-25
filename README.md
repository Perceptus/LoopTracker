# LoopTracker
Simple Following of Loop BG, IOB, Active Carbs and Basal Rate
# Description
- Simply Plot Data From Nightscout Uploads from Loop
- Graphs Do NOT Spline Thru Missing Data Points to Avoid Rendering False Information
- Automatically Refreshes At User Defined Interval
- Enter https://yoururl At the Bottom of the App - Saves With Local Storage
- LoopDate and DeviceDate Are the "created_at" Dates from Uploads from Loop to NS
  
# Issues
- Safari on iOS Does NOT Seem to Save User URL Via Local Storage - Not Sure Why - I Use Chrome on iOS
- If You Run index.html from a File In Your DeskTop Browser You Need to Allow Cross Origin
-- Chrome Requires an Extension
-- Safari Has a User Setting
- If You Run index.html from a Static Website You Need to Enable cors In NightScout Settings and Add the URL Of Your Website
- I Am NOT Planning on Major Updates / Fixes as This is An Interim Measure Before Folks Develop a Real Follower App for Loop, But Feel Free to Submit Fixes and Improvements.
- Basal Rates Shown are ONLY Those Enacted.  Therefore if You Are Not Always Enacting Temps per @elnjensen Modifications You Will Get a Very Sparse Graph Sorry :)  If Someone Wants to Pull In and Create Basal Data From NS Profiles That Would Be Great.
  
  
 # Credits
  - All the Amazing Folks Who Developed Loop - @ps2, @loudnate, @kdisimone
  - HighCharts.js
  
![alt text](https://raw.githubusercontent.com/Perceptus/LoopTracker/master/looptrackerexampleimage.png)
