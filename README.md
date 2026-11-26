<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d9ff,100:0d1117&height=120&section=header&text=&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=760&lines=Hi%2C+I'm+Fahad+Bin+Shafi+%F0%9F%91%8B;AI+%2F+Machine+Learning+Engineer-in-training;Computer+Vision+%7C+Deep+Learning+%7C+Flutter)](https://git.io/typing-svg)

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-Fahad--Bin--Shafi-0d1117?style=flat-square&logo=github&logoColor=white)](https://github.com/Fahad-Bin-Shafi)
&nbsp;
![Focus](https://img.shields.io/badge/Focus-Computer_Vision_%7C_Deep_Learning-00d9ff?style=flat-square)
&nbsp;
![Interests](https://img.shields.io/badge/Interests-MLOps_%7C_DevOps-blueviolet?style=flat-square)

</div>

---

## About Me

I'm a **BS Artificial Intelligence** student at COMSATS University Islamabad, building towards a career as an **AI / Machine Learning Engineer**. My work so far is centred on **computer vision and deep learning**: benchmarking pretrained CNNs on medical images, comparing classical and learned feature pipelines, and running controlled experiments where only one variable changes at a time. Alongside ML, I build **cross-platform mobile apps with Flutter**.

I care about doing experiments properly: leakage-free data splits, fixed seeds, honest baselines, and writing up what *didn't* work as well as what did.

```python
fahad = {
    "role"             : "AI/ML student, BS Artificial Intelligence",
    "currently_working": ["Stride: AI-powered gym coaching app (Flutter + Supabase)", "Computer vision experiments on medical imaging"],
    "exploring"        : ["MLOps", "DevOps practices for ML systems"],
    "open_to"          : ["Internships", "Project collaborations", "Open-source contributions"],
}
```

---

## Tech Stack

<div align="center">

**💻 Languages**

[![Skills](https://skillicons.dev/icons?i=python,dart,ts&theme=dark)](https://skillicons.dev)

**🧠 Deep Learning & Machine Learning**

[![Skills](https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark)](https://skillicons.dev)
&nbsp;
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)

**👁️ Computer Vision**

[![Skills](https://skillicons.dev/icons?i=opencv&theme=dark)](https://skillicons.dev)
&nbsp;
![scikit-image](https://img.shields.io/badge/scikit--image-F7931E?style=flat-square)
![SIFT](https://img.shields.io/badge/SIFT-Feature_Matching-0097A7?style=flat-square)
![HOG](https://img.shields.io/badge/HOG-Descriptors-0097A7?style=flat-square)

**📊 Data Science**

[![Skills](https://skillicons.dev/icons?i=numpy,pandas&theme=dark)](https://skillicons.dev)
&nbsp;
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)

**📱 Mobile & Web**

[![Skills](https://skillicons.dev/icons?i=flutter,react,vite&theme=dark)](https://skillicons.dev)
&nbsp;
![Riverpod](https://img.shields.io/badge/Riverpod-State_Management-00B0FF?style=flat-square)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**⚙️ Tools & Platforms**

[![Skills](https://skillicons.dev/icons?i=git,github,vscode&theme=dark)](https://skillicons.dev)
&nbsp;
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)

</div>

> **MLOps & DevOps** are an area I'm actively exploring. I'm listing them as interests, not skills, until I have shipped work to show for them.

---

## Featured Projects

All projects below live in [**Computer-Vision-Coursework**](https://github.com/Fahad-Bin-Shafi/Computer-Vision-Coursework), a lab series from my Computer Vision course. Each lab has its own README with dataset, method, results, and limitations.

<table>
<tr>
<td width="50%" valign="top">

### 🔬 Filtering vs. Skin-Lesion Classification
![Runs](https://img.shields.io/badge/Training_Runs-18-00d9ff?style=flat-square)
![Dataset](https://img.shields.io/badge/Dataset-HAM10000-blue?style=flat-square)

**Question:** does classical image filtering help or hurt a CNN on dermoscopy images? Three CNNs (ResNet50, DenseNet121, ResNet101) × six conditions (no filter, average, Gaussian, median, sharpen, Sobel), with a **lesion-level split** to prevent train/test leakage. Finding: Sobel-only input cost every model about 20 accuracy points; other filters moved results by a few points, with the sign depending on the model.

`PyTorch` `OpenCV` `ResNet` `DenseNet` `HAM10000`

[→ View Lab](https://github.com/Fahad-Bin-Shafi/Computer-Vision-Coursework/tree/HEAD/Lab02)

</td>
<td width="50%" valign="top">

### 🧬 GA-Optimised HOG Features for Pneumonia Detection
![Features](https://img.shields.io/badge/Features-8100→2312-brightgreen?style=flat-square)
![F1](https://img.shields.io/badge/Macro--F1-%2B3.27_pp-00d9ff?style=flat-square)

**Question:** can a Genetic Algorithm pick better HOG features for chest X-ray classification? GA feature selection removed **71.5% of features** and improved test macro-F1 by **3.27 points** (95% CI [+1.44, +5.35], paired bootstrap) over a full-feature HOG + RBF-SVM baseline, with the limitations documented.

`HOG` `Genetic Algorithm` `SVM` `scikit-learn` `PyTorch`

[→ View Lab](https://github.com/Fahad-Bin-Shafi/Computer-Vision-Coursework/tree/HEAD/Lab%2007)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧪 Transfer Learning vs. Deep Features + Classical ML
![Models](https://img.shields.io/badge/Models-3_CNNs_+_7_classifiers-00d9ff?style=flat-square)
![Dataset](https://img.shields.io/badge/Dataset-ISIC_9_Classes-blue?style=flat-square)

Benchmarks end-to-end fine-tuning (VGG16, ResNet18, EfficientNet-B0) against ResNet18 deep features fed to seven classical classifiers (LogReg, Decision Tree, Random Forest, KNN, Linear/RBF-SVM, XGBoost), comparing accuracy, parameters, FLOPs, and inference time.

`PyTorch` `scikit-learn` `XGBoost` `Transfer Learning`

[→ View Lab](https://github.com/Fahad-Bin-Shafi/Computer-Vision-Coursework/tree/HEAD/Lab1)

</td>
<td width="50%" valign="top">

### 🗼 Landmark Recognition with SIFT
![Landmarks](https://img.shields.io/badge/Landmarks-5_+_Unknown_Class-00d9ff?style=flat-square)
![Verification](https://img.shields.io/badge/Verification-RANSAC_Homography-brightgreen?style=flat-square)

Recognises landmarks from a query photo using SIFT descriptors, Lowe's ratio test, and RANSAC homography verification, with a multi-condition decision rule that **rejects unknown landmarks** instead of forcing a guess. Evaluated under rotation, scale, brightness, and viewpoint changes, and the README reports where it fails.

`SIFT` `OpenCV` `RANSAC` `NumPy`

[→ View Lab](https://github.com/Fahad-Bin-Shafi/Computer-Vision-Coursework/tree/HEAD/LAB%2006)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ✂️ Edge Detection & Its Impact on Classification
![Images](https://img.shields.io/badge/Images-24%2C211-brightgreen?style=flat-square)
![Dataset](https://img.shields.io/badge/Dataset-ISIC_2019-blue?style=flat-square)

Compares Sobel, Prewitt, Laplacian, LoG and Canny under Gaussian and salt-and-pepper noise, tunes Canny thresholds, then tests whether classifying edge maps beats raw or sharpened images across 15 trained conditions (SVM, Random Forest, KNN, ResNet50, EfficientNet-B0).

`OpenCV` `Canny` `ResNet50` `EfficientNet` `ISIC 2019`

[→ View Lab](https://github.com/Fahad-Bin-Shafi/Computer-Vision-Coursework/tree/HEAD/Lab%2003)

</td>
<td width="50%" valign="top">

### 🧠 CNN Feature Visualization & Parameter Audit
![Models](https://img.shields.io/badge/Audit-Manual_=_Keras-brightgreen?style=flat-square)

Visualises how convolution, ReLU and max/average pooling transform an image across five fixed kernels, and verifies trainable-parameter counts of two Keras CNNs by hand (710 and 1,750 parameters, matching framework totals).

`Keras` `TensorFlow` `NumPy` `Matplotlib`

[→ View Lab](https://github.com/Fahad-Bin-Shafi/Computer-Vision-Coursework/tree/HEAD/Lab%2012)

</td>
</tr>
</table>

### 🚧 In Development

**Stride: AI-powered gym coaching app.** A Flutter mobile app (Dart, Riverpod, Supabase) with onboarding and an exercise library, currently in development. The repository is private for now.

---

## GitHub Statistics

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Fahad-Bin-Shafi&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)](https://github.com/Fahad-Bin-Shafi)
&nbsp;
[![GitHub Streak](https://streak-stats.demolab.com?user=Fahad-Bin-Shafi&theme=tokyonight&hide_border=true)](https://github.com/Fahad-Bin-Shafi)

</div>

## Contribution Graph

<div align="center">

[![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=Fahad-Bin-Shafi&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00d9ff&line=00d9ff&point=ffffff)](https://github.com/Fahad-Bin-Shafi)

</div>

---

<div align="center">

I'm looking for **AI/ML internships**, **computer vision and deep learning collaborations**, and **open-source contributions**. Feel free to open an issue on any repository or follow me on GitHub.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00d9ff,100:0d1117&height=80&section=footer" width="100%"/>

</div>
