# Natalie Chang Portfolio

Data science portfolio showcasing projects in cognitive science and spaceflight research.

## Projects
- Flow Cytometry Analysis - Interactive visualization of immune cell populations

## Technologies
Python, Plotly, Pandas, Jupyter Notebook
```
3. Save As:
   - Location: `my-portfolio\`
   - File name: `README.md`
   - Save as type: **All Files**

**Create `.gitignore`:**
1. Open Notepad
2. Copy this:
```
.ipynb_checkpoints/
__pycache__/
*.pyc
.DS_Store
```
3. Save As:
   - Location: `my-portfolio\`
   - File name: `.gitignore`
   - Save as type: **All Files**

**Create `requirements.txt`:**
1. Open Notepad
2. Copy this:
```
pandas>=2.0.0
numpy>=1.24.0
plotly>=5.14.0
jupyter>=1.0.0
```
3. Save As:
   - Location: `my-portfolio\`
   - File name: `requirements.txt`
   - Save as type: **All Files**

---

### **Step 2: Add Your Data & Plot Files**

**Copy your CSV file:**
- From: Where it currently is
- To: `my-portfolio\projects\flow-cytometry\data\`

**Copy ALL your HTML plot files:**
- From: Where Jupyter saved them
- To: `my-portfolio\projects\flow-cytometry\figures\interactive\`
- (All files like: slide1_overview.html, slide2_distributions.html, advanced_violin_plots.html, etc.)

---

### **Step 3: Verify Your Complete Structure**

Open File Explorer and check you have this:
```
my-portfolio\
├── index.html ✅
├── README.md ✅
├── .gitignore ✅
├── requirements.txt ✅
└── projects\
    └── flow-cytometry\
        ├── index.html ✅
        ├── data\
        │   └── [CSV file] ❓
        ├── notebooks\
        │   └── fcplots.ipynb ✅
        └── figures\
            └── interactive\
                └── [All HTML files] ❓