FROM python:3.10-alpine

RUN pip install pip --upgrade
RUN pip install blinker==1.6.2
RUN pip install click==8.1.7
RUN pip install Flask==3.0.0
RUN pip install itsdangerous==2.1.2
RUN pip install Jinja2==3.1.2
RUN pip install MarkupSafe==2.1.3
RUN pip install Werkzeug==3.0.0

# Copy project
COPY . .

EXPOSE 8888
CMD ["python3", "-u", "app.py", "-h", "0.0.0.0"]