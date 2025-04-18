# Parsing Difficulty Simulation & ANOVA (Python)

This mini-project simulates human sentence processing difficulty based on syntactic structure. It is inspired by classic psycholinguistic research and uses statistical analysis to compare simulated reading times for different sentence types.

## 💡 Project Goal

To model and analyze parsing difficulty in human language processing using Python and ANOVA. This project demonstrates basic cognitive modeling and statistical analysis relevant to cognitive science and psycholinguistics.

## 🧪 Method

- Simulated reading times for three sentence types:
  - **SVO** (Subject-Verb-Object) – e.g., "The dog chased the cat." (easy)
  - **Passive** – e.g., "The cat was chased by the dog." (moderate)
  - **OSV** (Object-Subject-Verb) – e.g., "The cat the dog chased." (harder)
- Generated 30 samples per sentence type using a normal distribution
- Ran **one-way ANOVA** to test for significant differences in reading times
- Visualized results with a **Seaborn boxplot**

## 📊 Tools & Libraries

- Python 3
- `numpy`, `pandas` 
- `statsmodels`
- `matplotlib`, `seaborn` 

## 📈 Output

- Console output: ANOVA summary table
- File output: parsing_difficulty_plot.png – shows simulated reading times for different sentence types

## 🔍 Relevance to Cognitive Science

This project reflects foundational concepts in psycholinguistics, such as parsing difficulty and sentence structure. It also demonstrates competence in empirical methods and statistical reasoning—key components in cognitive science research.

## 📁 File Structure
parsing_difficulty_project/
- parsing_difficulty.py
- parsing_difficulty_plot.png
- README.md
- .gitignore



## ✅ To Run

1. Make sure **Python 3** is installed on your system.

2.  Create a virtual environment:
   ```bash
   python -m venv venv
   # on macOS/Linux to activate venv:
   source venv/bin/activate
   # on Windows activate venv:
   venv\Scripts\activate
   
3. Install the required packages:
   pip install -r requirements.txt

4. Run the Python script:
   python parsing_difficulty.py



