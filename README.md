
# Customer Churn Prediction

In this repository, we have performed  end to end Exploratory Data Analysis, and idenfitied the characteristics of the customers that are more likely to churn, and on the basis of the analysis we have created a model, and lately, have deployed the model.





Creating Flask API

```bash
  app = Flask("__name__")
```
The loadPage method calls our home.html.

```bash
 @app.route("/")
def loadPage():
	return render_template('home.html', query="")
```
The predict method is our POST method, which is basically called when we pass all the inputs from our front end and click SUBMIT.
```bash
@app.route("/", methods=['POST'])
def predict():
```
The run() method of Flask class runs the application on the local development server.
```bash
app.run()
```
Our model is ready, let’s test our bot. The above given Python script is executed from Python shell.

Go to Anaconda Prompt, and run the below query.
```bash
python app.py
```