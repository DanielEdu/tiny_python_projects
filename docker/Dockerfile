FROM python:3.8.4-buster
RUN apt-get -y update
RUN apt-get install -y git vim emacs zsh git-core
RUN /usr/local/bin/python3 -m pip install --upgrade pip

WORKDIR /app
RUN git clone https://github.com/DanielEdu/tiny_python_projects.git
RUN python3 -m pip install -r /app/tiny_python_projects/requirements.txt

CMD ["python3", "--version"]