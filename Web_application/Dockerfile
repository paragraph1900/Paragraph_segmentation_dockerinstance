FROM python:3.7-buster

WORKDIR /app

# Install requirements
COPY requirements.txt .
RUN pip install -r requirements.txt
RUN pip install -U scikit-learn

# Copy source code
COPY . /app

# expose the port number to outsiders
EXPOSE 5000

# Run application
CMD ["python","app.py"]