# supML
After importing data and doing a little cleaning we began with the Random Oversample aglo. This yielded a .63 precision and a f1 of .77. Next was the Smote Algo; this yielded a .647 precision and a f1 of .81. Next was the Cluster centroid, this yielded a .58 precision and f1 of .71. Lastly, before decision tree methods, was the Smooteenn algo; this yielded a .658 and a f1 of .74. For the challenge portion of the exercise the Smooteen was the most precise and had the highest f1. 

I would conclude that the Smooteenn method was most effective. On the flip side, the tactic of under sampling only seems to have yielded the worst results. I would assume this is because of the disparity in the classes. 

Next, we moved onto the decision tree methods, these both yielded far better results. Random Forest yielded a .924 precision and .97 f1 score. Which out preformed the Adobos with a .941 precision and .97 f1 score. 

Overall the balanced approach seems to have yielded the best results. Maximizing the # of positive inputs and decreasing the overall # of inputs seems to have allowed the algo to create a best result overall. Overall with all part of the challenge completed, I suggest the Balanced Random Forest Classifier method, it has the highest precision and highest f1 – which for this dataset seems logical.