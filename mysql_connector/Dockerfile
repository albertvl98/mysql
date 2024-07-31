FROM homeassistant/amd64-base:latest
RUN pip install mysql-connector-python
COPY run.sh /
RUN chmod a+x /run.sh
CMD [ "/run.sh" ]
