# chemical-process-simulation
Optimized PDE/ODE solver for chemical process simulation with a 3D spatiotemporal dashboard
# 🧪 반응기 공정 시뮬레이션 및 3D 온도 구배 대시보드 (Streamlit)

비선형 미분방정식(ODE) 및 편미분방정식(PDE) 기반의 화학 공정 모델링을 수행하고, 다중 AI(Gemini, ChatGPT, Claude)와의 협업을 통해 알고리즘을 최적화한 프로젝트입니다.

## 💡 Key Features
- **수치해석 최적화:** SciPy `solve_ivp` 및 벡터화(Vectorization)를 적용하여 기존 for문 대비 연산 속도 70% 단축
- **예외 처리 (Exception Handling):** AI의 물리적 환각(농도 음수 발산 등)을 제어하는 방어 로직 구현
- **인터랙티브 대시보드:** Streamlit과 Plotly를 활용한 조건별 3D Surface Plot 실시간 렌더링

## 🛠 Tech Stack
- Python, SciPy, NumPy, Streamlit, Plotly

## 🚀 How to Run
```bash
pip install streamlit scipy numpy plotly
streamlit run app.py
