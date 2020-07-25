# covid-19-pneumonia
# covid-19-pneumonia
A basic model for detecting pneumonia in covid-19 pateints
I used Image Augmentation here because our tarining dataset is not that much.
Now the point to be noted here is that after svereal epochs my learning rate has been changed, it happened due to that callback function I used.
The problem I see here is that:
  1. After certain epochs validation accuray started swinging between some fixed values
  2. And same pattern is observed in Training accuracy also

I think these problem can be excluded somewhat reduced by:
 1. Using bigger dataset
 2. Try reducing value of minimum Learning rate in callbacks
 3. Using Dropouts more efficiently
 
