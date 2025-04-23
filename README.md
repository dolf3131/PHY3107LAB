# 물리학실험B 분석 코드 모음 (Experimental Physics B Analysis Codes)

이 저장소는 물리학실험B(PHY3107)에서 수행하는 다양한 실험에 대해,  
파이썬을 이용한 데이터 처리 및 시각화 과정을 정리한 코드 모음입니다.

실험 데이터 및 매뉴얼은 포함되어 있지 않으며, 분석 과정에서 사용된 코드와 예제 시각화 결과만 포함되어 있습니다.

## 📘 주요 기능
- X-ray 회절 분석: Bragg’s law 기반 회절각 및 파장 계산
- 피크 검출: `scipy.signal.find_peaks`를 이용한 자동화된 피크 탐지
- 오차 분석: 상대 오차 및 고차 회절 검증
- 최소 파장 추정 및 Duane-Hunt 관계 확인
- 다양한 실험 유형에 대응하는 범용 분석 템플릿

## 🗂️ 구성
├── src/ # 분석 코드 (.py) ├── notebooks/ # Jupyter 노트북 예시 ├── images/ # 예제 출력 그래프 ├── requirements.txt # 사용된 라이브러리 목록 └── README.md

## ⚠️ 주의사항
- 본 저장소에는 실험 원본 데이터(.csv, .pdf 등) 및 학교 제공 매뉴얼은 포함되어 있지 않습니다.
- 모든 코드는 교육 및 학습 목적이며, 실험 장비 또는 학과의 공식 자료가 아닙니다.


# Experimental Physics B – Analysis Code Collection (PHY3107)

This repository contains Python code templates for analyzing experimental data  
from various laboratory sessions in the Experimental Physics B course (PHY3107).

It includes general-purpose scripts and Jupyter notebooks for peak detection, diffraction analysis, and visualization.  
**No raw experimental data or official university manuals are included.**

## 📘 Features
- Bragg diffraction analysis and wavelength calculation
- Automatic peak detection using `scipy.signal.find_peaks`
- Error analysis and higher-order diffraction validation
- Duane-Hunt relation and minimum wavelength estimation
- Modular analysis templates for multiple experimental types

## 🗂️ Directory Structure
├── src/ # Python analysis scripts ├── notebooks/ # Jupyter Notebook examples ├── images/ # Sample result visualizations ├── requirements.txt # Required Python packages └── README.md


## ⚠️ Notes
- This repository does **not** include any experimental data files or institutional materials.
- All code is for **educational and demonstrative purposes only**, and not affiliated with any official university resources.

