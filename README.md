# review_torch


# PyTorch 연산 및 모델링 연습

PyTorch를 사용한 기초 연산 및 간단한 모델링 연습을 위한 주피터 노트북

## 개요

이 프로젝트는 다음과 같은 내용을 포함함
- PyTorch 설치 및 기본 연산
- 텐서 조작 및 연산
- 간단한 인공신경망 모델 구현 및 학습
- 모델 평가 및 시각화

## 설치

프로젝트 실행을 위한 패키지들을

```bash
# 가상환경 생성 (선택사항)
python -m venv pytorch_env
source pytorch_env/bin/activate  # 윈도우의 경우 pytorch_env\Scripts\activate

# 필수 패키지 설치
pip install torch torchvision torchaudio
pip install jupyter
pip install matplotlib
pip install numpy
