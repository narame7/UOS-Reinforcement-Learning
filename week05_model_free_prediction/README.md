# Week 05 · Model-Free Prediction (모델 없는 예측)

강의 슬라이드: *Week 05 - Model-Free Prediction*

| 노트북 | 내용 | Colab |
|---|---|---|
| [01_monte_carlo_prediction.ipynb](01_monte_carlo_prediction.ipynb) | First-/Every-Visit MC, Blackjack 가치 함수(10,000 / 500,000 에피소드, S&B Fig. 5.1), Incremental Mean, Incremental MC Updates | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/narame7/UOS-Reinforcement-Learning/blob/main/week05_model_free_prediction/01_monte_carlo_prediction.ipynb) |
| [02_td_prediction.ipynb](02_td_prediction.ipynb) | Driving Home(MC vs. TD, The Numbers Behind the Arrows), Bias/Variance, Random Walk: MC vs. TD(추정값 · RMS 곡선), Batch MC and TD, AB Example, Certainty Equivalence(S&B Fig. 6.2) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/narame7/UOS-Reinforcement-Learning/blob/main/week05_model_free_prediction/02_td_prediction.ipynb) |
| [03_n_step_td_lambda.ipynb](03_n_step_td_lambda.ipynb) | Large Random Walk의 n-step TD(S&B Fig. 7.2), Averaging n-Step Returns, TD(λ) Weighting Function, Forward-View TD(λ)(Fig. 12.3), Eligibility Traces, Backward-View TD(λ)(Fig. 12.6), Forward = Backward / TD(1) = MC 수치 확인 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/narame7/UOS-Reinforcement-Learning/blob/main/week05_model_free_prediction/03_n_step_td_lambda.ipynb) |
| [04_example_problems.ipynb](04_example_problems.ipynb) | 슬라이드 Example Problem 1–5 풀이(first-/every-visit MC, TD(0) 손 계산, batch MC vs. TD, n-step·λ-return, eligibility trace)와 Quick Check 정답, 작은 확인 실험 | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/narame7/UOS-Reinforcement-Learning/blob/main/week05_model_free_prediction/04_example_problems.ipynb) |
