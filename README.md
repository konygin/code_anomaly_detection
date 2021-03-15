# Code anomaly detection

#### `results/`

The most anomalous code (methods) found by the model, learned on the train part of the dataset [Py150](https://www.sri.inf.ethz.ch/py150):
- `py150_test_anomalies.txt`: test part of the dataset [Py150](https://www.sri.inf.ethz.ch/py150)

The methods sorted in descending order of the anomaly score. Example:
```
         ====================================================================================================
SCORE-->  52.211
PATH -->  source_files/data/tav/plexnet/third_party/generic/pypy/lib-python/2.5.2/plat-freebsd7/IN.py
LINES-->  420:421
         ----------------------------------------------------------------------------------------------------
CODE --> def IN6_IS_ADDR_MC_NODELOCAL(a): return \
``` 

#### `checkpoints/`

- `scaler.pickle`: scaler
- `vae.pth`: variational autoencoder
