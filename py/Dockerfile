#our image will be created using python
FROM 192.168.0.10:5000/python

#execute the following comand at the timeof building the image
RUN pip install flask

# set current working directory
WORKDIR /src

# copy the program file
# here second parameter (.) represents the working directory (/src)
# copy 

COPY . . 

EXPOSE 4000
CMD python server.py


