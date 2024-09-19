
# **Market Analysis Lab for the Apartment Sector**

Below you will find a script for parsing data from the [House.kg](https://www.house.kg/kupit-kvartiru) website. There is also a parsing script `main.py` that you can run.
Retrieve new data and compare the market conditions with historical data `flats.csv` from September 2024.


When running the script, you need to specify the number of pages you want to parse. Each page on the website contains 10 listings.
There can be around 648 pages in total, but verify this number on the [website](https://www.house.kg/kupit-kvartiru).


```
git clone https://github.com/pwoakk/house_kg.git
cd house
pip install -r requirements.txt

python main.py
```

The author of the parser is https://github.com/IslamJenishbekov
You can see the original code at the link: https://github.com/IslamJenishbekov/flats_project_house_kg.git
