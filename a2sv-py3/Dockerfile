FROM python:3

ADD * ./

RUN pip install -r requirements.txt

ENTRYPOINT ["python","a2sv.py"]

# Build
# docker build -t a2sv .
# Run
# docker run a2sv -t example.com
