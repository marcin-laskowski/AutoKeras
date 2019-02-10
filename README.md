# AutoKeras

AutoKeras is open source software library for automated machine learning (AutoML).

## INSTALLATION
To install the package, please use the pip installation as follows:
```
pip install autokeras
```

## EXAMPLE
Here is a short example of using the package.
```
import autokeras as ak

clf = ak.ImageClassifier()
clf.fit(x_train, y_train)
results = clf.predict(x_test)
```
