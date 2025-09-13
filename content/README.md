# Open-LLM-VTuber
Original Github: https://github.com/Open-LLM-VTuber/Open-LLM-VTuber

### Youtube Reference
#### Open-LLM-VTuber Running on VPS
<p align="center">
  <a href="https://www.youtube.com/watch?v=JefGof3G-o8" target="_blank">
    <img src="https://img.youtube.com/vi/JefGof3G-o8/0.jpg" alt="YouTube Video Thumbnail" width="480" />
  </a>
</p>
Click the image above to watch the video

#### Steps Run Open-LLM-VTuber on VPS
<p align="center">
  <a href="https://www.youtube.com/watch?v=JefGof3G-o8" target="_blank">
    <img src="https://img.youtube.com/vi/JefGof3G-o8/0.jpg" alt="YouTube Video Thumbnail" width="480" />
  </a>
</p>
Click the image above to watch the video

##### 1. Update & Install
```
sudo apt update && sudo apt upgrade -y
sudo apt install -y git python3 python3-venv python3-pip curl
```


##### 2. Clone Repository
```
git clone --recursive https://github.com/Open-LLM-VTuber/Open-LLM-VTuber.git
cd Open-LLM-VTuber
```

##### 3. Prepare Python Virtual Env
```
cd Open-LLM-VTuber
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip setuptools wheel packaging
pip install -r requirements.txt
```

##### 4. Install modules
```
pip install pyyaml ruamel.yaml uvicorn loguru fastapi websockets requests tomli packaging chardet numpy mcp anthropic openai pysbd langdetect jinja2 Letta pydub sherpa_onnx edge_tts
```

##### 5. Install ffmpeg
```
sudo apt install -y ffmpeg
```

##### 6. Setting conf.yaml
Run python run_server.py to make conf.yaml
```
python3 run_server.py
```