FROM python
RUN pip install flask
RUN pip install requests
COPY  ./templates /home/myapp/templates/
COPY  ./static /home/myapp/static/
COPY  app.py /home/myapp/
EXPOSE 5050
CMD python3 /home/myapp/app.py
