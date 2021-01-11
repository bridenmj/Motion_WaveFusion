# WaveFusion Model for Motion Dataset

## Steps to run notebook:

``kubectl exec -it <pod-hash> bash``

``jupyter notebook --ip='0.0.0.0'``

Open another terminal window and execute the following
``kubectl port-forward <pod-hash> 8888:8888``

Go to web browser and enter ``localhost:8888``

Open or upload the desired notebook and run it