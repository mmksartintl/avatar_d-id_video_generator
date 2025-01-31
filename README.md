# avatar_d-id_video_generator
Generates a video from prompt utilizing D-ID avatars

Implements:
- Uses D-ID avatar library to create videos https://www.d-id.com
- Streamlit in Python to user interface https://flask.palletsprojects.com/en/stable/

Steps:

1) run a docker image

   $ docker container run -d -p 8501:8501 python:3.10 sleep infinity

2) pip install streamlit

3) streamlit run main.py
