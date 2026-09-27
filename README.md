# UOS Reinforcement Learning — 강의 예제 노트북

서울시립대학교 **강화학습** 강의 슬라이드에 나오는 예제를 직접 실행하고 시각화해 볼 수 있는 Jupyter 노트북 모음입니다.
각 노트북은 슬라이드의 예제를 같은 설정으로 구현하고, 슬라이드에 적힌 수치와 계산 결과를 나란히 비교합니다.
강의 진도에 맞춰 매주 업데이트됩니다.

## 주차별 노트북

주차 번호는 강의 슬라이드 파일명(`Week NN - ...`)을 따릅니다.

| 주차 | 주제 | 노트북 |
|:---:|---|---|
| [01](week01_introduction) | **Introduction to Reinforcement Learning**<br>강화학습 소개 | [Returns and the Maze Example — 반환값과 미로 예제](week01_introduction/01_returns_and_maze.ipynb) · [Colab](https://colab.research.google.com/github/narame7/UOS-Reinforcement-Learning/blob/main/week01_introduction/01_returns_and_maze.ipynb)<br>[Gridworld: Prediction and Control — 그리드월드: 예측과 제어](week01_introduction/02_gridworld.ipynb) · [Colab](https://colab.research.google.com/github/narame7/UOS-Reinforcement-Learning/blob/main/week01_introduction/02_gridworld.ipynb) |
| 03 | **Markov Decision Process**<br>마르코프 결정 과정 | 강의 진도에 맞춰 공개 예정 |
| 04 | **Planning by Dynamic Programming**<br>동적 계획법 | 강의 진도에 맞춰 공개 예정 |
| 05 | **Model-Free Prediction**<br>모델 프리 예측 | 강의 진도에 맞춰 공개 예정 |
| 06 | **Model-Free Control**<br>모델 프리 제어 | 강의 진도에 맞춰 공개 예정 |
| 07 | **Value Function Approximation**<br>가치 함수 근사 | 강의 진도에 맞춰 공개 예정 |
| 08 | **Policy Gradient**<br>정책 경사 | 강의 진도에 맞춰 공개 예정 |
| 09 | **Natural Policy Gradient, TRPO, and PPO**<br>자연 정책 경사, TRPO, PPO | 강의 진도에 맞춰 공개 예정 |
| 11 | **Integrating Learning and Planning**<br>학습과 계획의 통합 | 강의 진도에 맞춰 공개 예정 |
| 12 | **Exploration and Exploitation**<br>탐험과 활용 | 강의 진도에 맞춰 공개 예정 |
| 13 | **Classic Games**<br>고전 게임 | 강의 진도에 맞춰 공개 예정 |

## 실행 방법

- **GitHub에서 바로 보기** — 모든 노트북은 실행 결과(그래프 포함)가 저장된 상태로 올라가 있습니다.
- **Google Colab** — 각 노트북의 `Colab` 링크(또는 노트북 상단 배지)를 누르면 별도 설치 없이 실행할 수 있습니다.
- **로컬 실행**

  ```bash
  git clone https://github.com/narame7/UOS-Reinforcement-Learning.git
  cd UOS-Reinforcement-Learning
  pip install -r requirements.txt
  jupyter lab
  ```

대부분의 노트북은 `numpy`와 `matplotlib`만 사용하며, 일부(CartPole 등)는 `gymnasium`, 신경망 예제는 `torch`를 사용합니다.
모든 노트북은 노트북 PC의 CPU에서 몇 분 안에 끝나도록 설정되어 있습니다.

## 참고 자료

- R. S. Sutton and A. G. Barto, *Reinforcement Learning: An Introduction*, 2nd ed., MIT Press, 2018. ([무료 PDF](http://incompleteideas.net/book/the-book-2nd.html))
- D. Silver, *UCL Course on Reinforcement Learning*, 2015.
- Paderborn University LEA, [*Reinforcement Learning Course Materials*](https://github.com/upb-lea/reinforcement_learning_course_materials).
