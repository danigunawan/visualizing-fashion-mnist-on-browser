# visualizing-fashion-mnist-on-browser
Training Fashion MNIST dataset on browser using tensorflowjs and visualizing model training using tfvisualizer js library.

# Running file:
Even though training occurs on static html files, tfjs libraries requires a server for serving the files. On website server is provied by hosting provider. 

Running file locally is also easy, as we need a server. There are many ways to serve http files like WAMP for windows or LAMP for linux, or chrome web http extension.

The simplest way to serve these file is by running one line python command inside folder containg files.

## Run python server inside project folder

```bash
python3 -m http.server
```
 The above command will give following output:
 ```
 Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...
 ```

 ## Open browser and goto link

## You will see html file along with other files on chrome browser

## Click on html file
This will open html file and start loading the tfjs.

# After opening file the training will start along with visualizer. Wait for training to finish. Once the training is finished an alert will pop up showing training is done.
# Now you can try drawing an input inside canvas after that click on classify to identify class from given input.