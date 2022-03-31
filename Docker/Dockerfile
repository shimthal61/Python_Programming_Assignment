FROM python:3.10

ADD README.md .
ADD Program_Script .
ADD data.csv .

RUN pip install numpy pandas seaborn matplotlib scipy statsmodels

CMD [ "python", "./Program_Script" ]