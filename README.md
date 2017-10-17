<p align="center">
  <h2 align="center">Enterprise Distributed Systems 273-Assignment-1</h2>
</p>

#Technology Used

<img src="http://i65.tinypic.com/2zp1hr9.png" height="120" width="120" hspace="20" > <img src="http://i67.tinypic.com/2yv6i9v.png" height="160" width="200" hspace="20"> <img src="http://i65.tinypic.com/fn4uow.png" height="100" width="150" hspace="20">

#Requirements to Run This Project
python version 3.6.2
#Instructions
1. Redis Datastructure must be installed to run this project <br />
   Please follow <a href="https://redis.io/topics/quickstart">Redis Installation Instruction</a>

2. Start the Redis server in a separate terminal by typing redis-server <br />
3. git clone https://github.com/loftywaif002/273-Assignment-1-Flask-Redis.git <br />
4. cd 273-Assignment-1-Flask-Redis <br />
5. You have to be inside the vistual Environment <br />
6. If you do not have vitual environment installed, then install it by typing pip install virtualenv <br />
7. Start Vitual Environment source venv/bin/activate <br />
8. Install all the dependencies that are needed to run the project <br />
   a. pip install redis <br />
   b. pip install uuid <br />
   c. pip install flask_json <br />
   d. any other dependcies that are missing in this list <br />
9. In a separate terminal, inside the 273-Assignment-1-Flask-Redis folder, do python3 app.py to run the  server <br />
10. In another terminal, go inside the 273-Assignment-1-Flask-Redis folder, and make POST request by copy pasting the code below <br />

```curl -i -X POST -H "Content-Type: multipart/form-data" 
-F "data=@foo.py" http://localhost:8000/api/v1/scripts
```
11. For get request, please copy paste the id that is generated in the terminal paste at the place where <script_id> is right now

```curl -i
http://localhost:8000/api/v1/scripts/<script_id>
```
#Screenshots <br />

<img src="http://i67.tinypic.com/ogfkap.png" height="400" width="800">
<img src="http://i67.tinypic.com/jq2c6q.png" height="300" width="750">
<img src="http://i66.tinypic.com/mjy0qa.png" height="300" width="750">
<img src="http://i64.tinypic.com/2jcwubr.png" height="300" width="750">
<img src="http://i63.tinypic.com/2a79yxv.png" height="300" width="750">
