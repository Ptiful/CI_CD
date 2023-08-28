FROM python:3.11
RUN mkdir /hln_scrapper
COPY . /hln_scrapper
WORKDIR /hln_scrapper
RUN pip install -r requirements.txt
CMD [ "python", "hln_articles.py"]