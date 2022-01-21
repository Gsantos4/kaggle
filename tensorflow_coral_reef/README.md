<h1> Kaggle Project: Coral Reef - Object Detect: crown-of-thorns starfish </h1>

<h3>Ideas</h3>

#transform to html list later

1. FathomNet
2. Yolov5 high augmentation + extra?
3. SimCLRv2

Steps

1. test collab with succesfully running yolov5 to learn flow + requirements to get yolov5 running and record results
2. learn how to unfreeze model to change weights and see how to save new model
3. learn how to load model with saved weights, freeze, and run on different dataset
4. Play around with yolov5 to see how easy/hard it is to implement high augmentation
5. in a seperate notebook learn how to import FathomNet data and convert annotations to some useful by yolov5
6. train, unfrozen, yolov5 on FathomNet, then run on Kaggle data
7. Record results
8. Stretch ideas
- explore how to use SimCLRv2
- apply SimCLRv2 to unlabeled starfish data (70% unlabelled)
