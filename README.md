# Repository for Machine Learning Studies

Studies of best seller: [Hands On Machine Learning with python book](https://www.amazon.com.br/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646/ref=asc_df_1492032646/?tag=googleshopp00-20&linkCode=df0&hvadid=379733272930&hvpos=&hvnetw=g&hvrand=5300540477099114985&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9100481&hvtargid=pla-523968811896&psc=1). 


### Run notebooks

Create virtualenv (tested on python3.9): 

```
virtualenv -p python3.9 venv
```

Setup venv: 

```
source venv/bin/activate
```

Install pip-compile tool

```
pip install pip-tools
```

Compile requirements.txt specified in `requirements.in` 

```
pip-compile
```

Install dependences using the `requirement.txt` file created by the command above: 

``` 
pip install -r requirements.txt

```
