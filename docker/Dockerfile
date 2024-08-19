FROM python:3.8

WORKDIR /usr/src/app

COPY . .

LABEL mainteiner=@juan1rving

RUN pip install  --no-cache-dir -r requirements.txt

EXPOSE 5000

ENTRYPOINT [ "/usr/bin/bash" ]

CMD ["python","./app.py"]