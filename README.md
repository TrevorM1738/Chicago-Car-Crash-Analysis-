# Chicago-Car-Crash-Analysis-
First I removed about 30 columns off of the initial data set that would not be need such as the id number for the crashes or columns that where mostly NaNs to try and keep a larger data set. 

Then I got rid of ambiguous data such as “Unknown” and “Unable to Determine’’

Then I decided to drop the rest of the NaNs

Also grouped data into larger groups from the primary cause category so there was not too many dummy variables created.

![](https://github.com/TrevorM1738/Chicago-Car-Crash-Analysis-/blob/main/picture/rename.png)

weather doe not have much of an imact as to when crashe happen 

![](https://github.com/TrevorM1738/Chicago-Car-Crash-Analysis-/blob/main/picture/chrash%20hour.png)

Chicago should focus on the peak hours of 8:00 in the morning and 5:00 in the after noon is when you see spikes in car chrashes.

![](https://github.com/TrevorM1738/Chicago-Car-Crash-Analysis-/blob/main/picture/chicago1heatmap.png)
![](https://github.com/TrevorM1738/Chicago-Car-Crash-Analysis-/blob/main/picture/chicago2heatmap.png)

This is a heat map of where the crashed happened in Chicago using the location data from the data set. the red indicates where most of ther crashes occured and the parts of the city that should be focused on the most when trying to prevent crashes. 

![](https://github.com/TrevorM1738/Chicago-Car-Crash-Analysis-/blob/main/picture/confusion%20matrix.png)

The final xgboost model I used had very high acuracy predicting driver negligance as the most common cause of car crashes whith the top two being following to closly and failing to yeild. 

# My Suggestions

Increase traffic patrols and focus on areas that are the highest rates of traffic accidents.
Pull people over for driver negligence particularly  following too closely and failing to yield.
Increase public awareness before the hot spots where crashes occur such as with signs.
