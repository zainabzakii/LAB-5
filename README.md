# LAB-5


I tested top_k = 3, 5, and 6 to reduce the number of categories in the Item_Name feature.
The accuracy remained almost the same across all values. This indicates that changing the number of top items did not significantly affect the model’s performance.

This suggests that Item_Name is not a highly influential feature in predicting the target. Instead, the model likely depends more on other features such as order time, quantity, and price-related features.
Therefore, adjusting top_k does not lead to noticeable improvement in accuracy in this case.
