# MARKET WATCH

It gives the real time market sentiment and stock prediction for the selected company.

### Data extraction
1. It uses [tiingo](https://www.tiingo.com/ "tiingo") to extract the stocks data.
2. It uses *beautifulsoup* to extract *News* from Economic times and Daily Political websites.
 
### Model Training
1.Diferent models have been trained on [PROPHET](https://facebook.github.io/prophet/docs/quick_start.html "PROPHET") for each of the five companies to predict the *stocks*.

2.To give the sentiment of the news [vader](https://pypi.org/project/vaderSentiment/ "Vader") is used.

#### Steps to run:
1. Clone the repo.
2. Install all the dependencies (A new environment would be prefered).
3. Download models folder from the [link](https://drive.google.com/drive/folders/19aBo28kOOL5T84n9UIBBJxNArqkuPC3D?usp=sharing "Link") and paste it in the directory which contains
 manage.py file.
4. Run manage.py by writing *python manage.py runserver* in the command propmt.
5. Copy the url generated and paste in the browser.
6. This is how it looks......

![download](C:\Users\rudra\Downloads\image (3).png)