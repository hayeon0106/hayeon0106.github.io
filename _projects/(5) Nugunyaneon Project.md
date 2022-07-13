---
name: 🗣📱 k-ditital training 해커톤 - 누구냐 넌
tools: [flutter, django, python, hackathon]
image:
description: 보이스피싱 통화 내용을 음성을 분석하여 얻은 보이스피싱 빈출 단어 데이터베이스를 활용하여 보이스피싱 여부를 판단하는 애플리케이션.
---

# 프로젝트 소개


🗣📱
  

보이스피싱 통화 내용을 음성을 분석하여 얻은 보이스피싱 빈출 단어 데이터베이스를 활용하여 보이스피싱 여부를 판단하는 애플리케이션이다.
  
사용자가 희망하는 통화 녹음 파일을 받아 애플리케이션 내에서 해당 음성 파일의 텍스트를 분석하여 보이스피싱 여부를 판단하고 보이스피싱으로 판단되었을 때, 사용자에게 대처 방법을 안내한다.


# 기술

> Python 3.9.12
  

> 데이터 분석  
> Python - KoNLPy 0.6.0의 Okt



> 모델링  
> Python - Pydub 0.25.1  
>          Pyaudio 0.2.11  
>          Tacotron1

  

> 개발  
> Flutter 3.0.1  
> Dart 2.17.1  
> Django 4.0.5  


  

# 결과

### 애플리케이션 화면

<p align="center">
 <img src="https://user-images.githubusercontent.com/84331957/176482243-6913555e-79b9-4b66-9c01-af4c009807d8.png" width="250"/>
 <img src="https://user-images.githubusercontent.com/84331957/176482326-53c19769-f8fa-41e4-9684-6cd6ab36ce81.png" width="250"/>
 <img src="https://user-images.githubusercontent.com/84331957/176482393-083d80c6-e060-4ff6-bbf1-42ad195465e6.png" width="250"/>
</p>

  

### 탐지 성능 분석

<p align="center">
 <img src = "https://user-images.githubusercontent.com/84331957/176482612-10574190-819c-46ef-abdb-ac2bf85e9489.png" width="700"/>
</p>


<p class="text-center">
{% include elements/button.html link="https://github.com/hayeon0106/nugunyaneon.git" text="Github" %}
</p>

<p class="text-center">
{% include elements/button.html link="https://www.notion.so/Django-d37ca22082b54ef7a091da560862e1f1" text="오류처리" %}
</p>