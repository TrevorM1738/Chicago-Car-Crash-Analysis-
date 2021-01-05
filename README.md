# Chicago-Car-Crash-Analysis-
First I removed about 30 columns off of the initial data set that would not be need such as the id number for the crashes or columns that where mostly NaNs to try and keep a larger data set. 

Then I got rid of ambiguous data such as “Unknown” and “Unable to Determine’’

Then I decided to drop the rest of the NaNs

Also grouped data into larger groups from the primary cause category so there was not too many dummy variables created.

!data:image/png;base64,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
