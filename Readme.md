## Installing using GitHub
- Fork the project into your GitHub
- Clone it into your dektop
```
git clone https://github.com/jacesca/pyspark-sales-forecasting.git
```
- Setup environment (it requires python3)
```
python -m venv venv
source venv/bin/activate  # for Unix-based system
venv\Scripts\activate  # for Windows
```
- Install requirements
```
pip install -r requirements.txt
```
- Required libraries
```
pip install pyspark
pip install findspark
pip install pandas
pip install pyspark[connect]
pip install pyspark[sql]
pip install plotly
pip install ipympl
pip install pyspark-dist-explore
pip install handyspark
```

