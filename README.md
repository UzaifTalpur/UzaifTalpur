<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1B3A6B,100:00b4d8&height=180&section=header&text=Uzaif+Talpur&fontSize=50&fontColor=fff&animation=fadeIn" width="100%"/>

<h3 align="center">AI Researcher · Computer Vision Engineer · Applied Deep Learning for Real-World Systems</h3>

<p align="center"><i>M.E. Information Technology (2026) · 4 publications · Seeking PhD positions in Computer Vision & Applied AI</i></p>

[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Uzaif-Talpur)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/uzaif-talpur)
[![Portfolio](https://img.shields.io/badge/Portfolio-1B3A6B?style=for-the-badge&logo=google-chrome&logoColor=white)](https://uzaiftalpur.netlify.app)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:uzaiftalpur@gmail.com)

</div>

---

## 👨‍🔬 About Me

I am an AI researcher and computer vision engineer from **Tando Muhammad Khan, Sindh, Pakistan** — a place that taught me early that power cuts, unenforced traffic laws, and thin infrastructure are not statistics but daily conditions. That shapes what I choose to work on: **deep learning systems that have to run on cheap hardware, in imperfect conditions, and still be useful.**

I have **completed my M.E. in Information Technology at Mehran UET Jamshoro** (GPA 3.91/4.0), including my **completed thesis, SolarEye** — a drone-vision system for solar panel detection and degradation mapping built to work with standard RGB cameras instead of $3,000 thermal rigs. My B.E. in Computer Systems Engineering is from the same university, funded by a national OGDCL merit scholarship.

My published work spans **computer vision for traffic enforcement, IoT sensing for energy optimisation, and applied software architecture for AI systems** — different application surfaces, one recurring question: *how do you get a working model out of a notebook and onto hardware someone can actually afford?*

Alongside research, I teach Python, AI, and web development under the Government of Sindh's PITP programme, write a Python book in Sindhi, judge and mentor for IEEE SSCS, and run plantation and STEM-outreach drives in my district.

**I am actively seeking a PhD position in Computer Vision, Applied Deep Learning, Remote Sensing / Spatial AI, or Edge & Embedded Intelligence.**

```python
uzaif = {
    "location"     : "Tando Muhammad Khan, Sindh, Pakistan 🇵🇰",
    "education"    : ["M.E. Information Technology — Mehran UET (Completed, GPA 3.91/4.0)",
                      "B.E. Computer Systems Engineering — Mehran UET (CGPA 3.66/4.0)"],
    "thesis"       : "SolarEye — Drone Vision for Scalable Solar Panel Detection & Mapping (Completed)",
    "publications" : "3 journal papers published · 1 book chapter under review",
    "interests"    : ["Computer Vision", "Remote Sensing & Spatial AI",
                      "Edge / Embedded Deep Learning", "Applied ML for Energy & Mobility",
                      "Signal & Spectrogram Intelligence"],
    "teaching"     : "Python → AI → Web Dev (PITP, Govt. of Sindh | Sep 2025 – May 2026)",
    "writing"      : "Python book in Sindhi 📖",
    "open_to"      : ["PhD Positions", "Research Collaborations", "Open-Source Contributions"],
}
```

---

## 📄 Publications

> ResearchGate: **[researchgate.net/profile/Uzaif-Talpur](https://www.researchgate.net/profile/Uzaif-Talpur)**

**1. Enhancing Traffic Law Enforcement through Deep Learning-Based Detection of One-Wheeler Motorcycle Stunts**
*Journal of Independent Studies and Research – Computing (JISR-C), SZABIST · Vol. 24, Issue 1*
YOLO-based real-time detection of illegal one-wheeler stunts, benchmarked for edge hardware deployment.
🔗 DOI: [10.31645/JISRC.26.24.1.7](https://doi.org/10.31645/JISRC.26.24.1.7)

**2. An Occupancy-Aware IoT-Based Framework for Real-Time Monitoring and Optimization of Energy Consumption in Smart Homes**
*Spectrum of Engineering Sciences · Vol. 4, Issue 3*
Sensor-driven occupancy inference feeding a real-time energy optimisation loop for residential systems.
🔗 DOI: [10.5281/zenodo.21425169](https://doi.org/10.5281/zenodo.21425169)

**3. An Extensible Model–View–Controller (MVC)-Based Cross-Platform Framework for Next-Generation AI-Enabled Email Applications**
*International Journal of Innovations in Science & Technology (IJIST) · Vol. 8, Issue 3*
Architecture pattern for embedding AI services into cross-platform client applications.
🔗 [Read the paper](https://journal.50sea.com/index.php/IJIST/article/view/1933/2833)

**4. Artificial Neural Networks in Financial Forecasting** — *Book Chapter, Under Review*
*Bentham Science Publishers*
ANN-based forecasting models evaluated against empirical financial case studies.

---

## 🔭 Research & Projects

### 🌞 SolarEye — M.E. Thesis *(Completed)*
> **A Deep Learning Based Drone Vision System for Scalable Solar Panel Detection and Mapping in Developing Regions**

End-to-end aerial inspection pipeline: **UAV imagery → OpenDroneMap 3D reconstruction → YOLO26 panel detection → soiling detection → heat-gain estimation → Folium dense heat mapping.** A Random Forest thermal regressor (R² 97.48%, MAE 0.82 °C) predicts panel surface temperature from RGB imagery and weather features, removing the dependency on thermal cameras. Detection module: mAP@50 0.532 on a custom aerial dataset — a deliberately hard, small-object, low-altitude-variance setting. Designed for sub-$500 hardware deployment in energy-deficient regions.

`PyTorch` `YOLO26` `OpenDroneMap` `Scikit-learn` `Folium` `Open-Meteo API` `OpenCV` `Pandas`

---

### 🏍️ One-Wheeler Stunt Detection *(Published)*
> **Deep Learning for Traffic Law Enforcement**

Full pipeline: YouTube frame extraction → Label Studio annotation → YOLOv11m training on a two-class custom dataset → real-time inference. Achieved ~0.90 mAP@50. **Published in JISR-C** — [DOI: 10.31645/JISRC.26.24.1.7](https://doi.org/10.31645/JISRC.26.24.1.7). Dataset release pending institutional clearance.

`YOLOv11m` `Label Studio` `OpenCV` `Python`

---

### 🏠 Occupancy-Aware Smart Home Energy Framework *(Published)*
> **IoT Sensing + Real-Time Optimisation**

IoT framework that infers room-level occupancy and drives real-time energy consumption monitoring and optimisation for residential buildings. **Published in Spectrum of Engineering Sciences** — [DOI: 10.5281/zenodo.21425169](https://doi.org/10.5281/zenodo.21425169).

`IoT` `Python` `Sensor Fusion` `Time-Series`

---

### 🔊 Cross-Domain Spectrogram Intelligence *(Ideation Stage)*
> **Deep Learning for Signal & Audio Domains**

Exploring cross-domain spectrogram analysis — treating signals from distinct acquisition domains as a shared visual representation problem for classification and anomaly detection.

`Signal Processing` `PyTorch` `Librosa` `CNNs`

---

### 👓 Smart Glasses for the Visually Impaired *(B.E. Thesis)*
Transfer learning on a pre-trained CNN for real-time object detection with audio feedback, deployed on Raspberry Pi. Demonstrated at university showcase; supported by the OGDCL Fully Funded Merit Scholarship.

`CNN` `Transfer Learning` `Raspberry Pi` `OpenCV`

---

## 📊 Completed Projects

| Project | Description | Stack |
|---|---|---|
| **BioScout — AI Nature Identification** | Multimodal species-identification app with live camera and conversational modes, built for field naturalists and educators | Google AI Studio, Multimodal LLM |
| **Real-Time Fruit Detection (Edge)** | MobileNet transfer learning on TensorFlow Lite; optimised for low-latency on-device inference | TensorFlow Lite, MobileNet |
| **Pakistan Budget Analyzer (Urdu)** | Public-facing tool simplifying the federal budget in Urdu for accessibility | Python, NLP, Streamlit |
| **Pakistan Job Market Forecasting** | 6,680+ postings analysed; 108% growth forecast via time-series, Random Forest + K-Means clustering | Scikit-learn, Matplotlib |
| **AI Property Investment Risk Analyzer** | ML-based risk scoring for property investment decisions | Python, Pandas, ML |
| **Indus Medical College Management System** | Offline-first desktop app: admissions, attendance, fees, analytics | Python, Tkinter, Pandas |
| **Burhan English Centre Management System** | Student admission and attendance system with dark UI and CSV storage | Python, Tkinter, PIL |
| **Bakery Sales Analysis** | Exploratory analysis and sales forecasting | Python, Pandas, Seaborn |

---

## 🎓 Advanced Training

| Programme | Focus | Year |
|---|---|---|
| **Cohere Labs ML Summer School** | Vision Transformers, self-supervised learning, DINOv2 / iBOT, foundation models — with researchers from Meta AI, Cohere, Inria | 2025 |
| **Hertie School Data Science Summer School** | Autonomous AI agents, experimental design, applied calculus for data science | 2025 |
| **IBM Applied Data Science Specialization** | 6-course specialisation: ML with Python, Deep Learning with Keras, data analysis | Coursera / IBM |
| **Google IT Support Professional Certificate** | Systems, networking, support operations | Google / Coursera |

---

## 💼 Experience

**Python & Web Development Instructor** — PITP, Government of Sindh @ University of Modern Sciences, TMK · *Sep 2025 – May 2026*
Designed and delivered curriculum in Python, web development, prompt engineering, and AI tooling to government-sponsored cohorts; led a mega project exhibition for Batches 2 and 4.

| Batch | Subject | Status |
|---|---|---|
| Batch 1 | Python Development | ✅ Completed |
| Batch 2 | Python Development | ✅ Completed |
| Batch 3 | Python Development | ✅ Completed |
| Batch 4 | Web Development (HTML, CSS, JS, Node.js, MongoDB) | ✅ Completed |

**Computer Vision Data Annotator (Freelance)** · *2023 – Present*
1,000+ images annotated across projects using LabelImg and Label Studio; tight bounding boxes, consistent labelling conventions, IoU best practices. Annotations used in production YOLO and TensorFlow Lite detection pipelines.

**Holistic Science Teaching Fellow** — PIF Islamabad · *2022* · Inquiry-based science pedagogy.
**IT Intern** — Government of Sindh · *2021* · Data security operations and Citizen Portal support.

---

## 🛠️ Tech Stack

**Computer Vision & Deep Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Ultralytics](https://img.shields.io/badge/YOLO%20(Ultralytics)-111F68?style=for-the-badge&logo=yolo&logoColor=white)
![DINOv2](https://img.shields.io/badge/DINOv2-0467DF?style=for-the-badge&logo=meta&logoColor=white)

**ML, Data & Statistics**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![SPSS](https://img.shields.io/badge/IBM%20SPSS-052FAD?style=for-the-badge&logo=ibm&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black)

**Geospatial & 3D**

![OpenDroneMap](https://img.shields.io/badge/OpenDroneMap-00A896?style=for-the-badge&logo=drone&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-77B829?style=for-the-badge&logo=leaflet&logoColor=white)
![GIS](https://img.shields.io/badge/GIS-2C7BB6?style=for-the-badge&logo=esri&logoColor=white)

**Web & Application Development**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**Tooling**

![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white)
![Label Studio](https://img.shields.io/badge/Label%20Studio-FF6B6B?style=for-the-badge&logo=label-studio&logoColor=white)

---

## 🏆 Honours, Recognition & Service

| Award / Role | Organisation | Year |
|---|---|---|
| 💰 **Research Grant — USD 6,000** | Koshish Foundation (competitive international, Tech for Good) | Active |
| 🎓 **OGDCL Fully Funded Merit Scholarship** | National undergraduate merit award | B.E. |
| 🎓 **Graduate Assistant Scholarship (offer)** | METU Northern Cyprus Campus | — |
| 🏅 **Judge, Mentor & Ambassador — Arduino Contest** | IEEE SSCS Society | 2026 |
| 🏅 **Judge — Arduino Contest** (international submissions) | IEEE SSCS Society | 2025 |
| 🌱 **Team Mentor — VibeSense** | IEEE SSCS Arduino Contest | 2025 |
| 🎤 **PITP Project Exhibition Lead** | University of Modern Sciences, TMK | 2026 |
| 🌿 **Regional Team Member** | STEAM Sindh, Government Project | Active |
| 🌏 **Global Green Forum** | Sustainability & energy policy research | — |
| 🤝 **Emergency Relief Pakistan** | Disaster response; 61,000+ member virtual community | — |
| 🗳️ **Election Campaign Agent** | Pakistan Engineering Council, District Level | Past |
| 📱 **Social Media Manager** | Sar-e-Aam (Iqrar ul Hassan Welfare Initiative) | 2018–2019 |

**Languages:** English (IELTS Academic 6.5, B2) · Urdu (Native) · Sindhi (Native)

---

## 🌱 On the Ground

Research is only part of the work.

- 🌳 **Plantation Drives** — organised tree plantation across District Tando Muhammad Khan with the DC, SSP, and police officials under the Sar-e-Aam welfare initiative
- 📚 **SDG Campaigns in Schools** — sustainability education at school and college level: organic composting, renewable energy basics, climate literacy
- 💻 **Digital Literacy** — teaching AI, coding, and prompt engineering to youth in remote Sindh
- 📖 **Python Book in Sindhi** — accessible programming resources in the local language
- 🎒 **Stationery Donations** — supporting students into STEM competitions and scholarships

---

## 🤝 Where I Want to Collaborate

- **Computer vision** — detection, segmentation, and self-supervised representation learning
- **Remote sensing & spatial AI** — UAV imagery, 3D reconstruction, geospatial mapping pipelines
- **Edge & embedded deep learning** — models constrained by cost, power, and latency
- **Applied ML for infrastructure** — energy systems, mobility, IoT sensing, public services
- **Signal + vision crossover** — spectrograms, sensor data, multimodal representations
- **AI for social good** in South Asia and other resource-constrained regions

---

## 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=UzaifTalpur&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00b4d8&icon_color=1B3A6B&text_color=ffffff" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=UzaifTalpur&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00b4d8&text_color=ffffff" height="165"/>

<img src="https://streak-stats.demolab.com/?user=UzaifTalpur&theme=tokyonight&hide_border=true&background=0D1117&ring=00b4d8&fire=1B3A6B&currStreakLabel=00b4d8" width="49%"/>

</div>

---

## 📬 Let's Connect

Open to conversations about research, PhD positions, collaborations, and ideas at the edge of AI and real-world infrastructure.

<div align="center">

[![ResearchGate](https://img.shields.io/badge/ResearchGate-Follow-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Uzaif-Talpur)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/uzaif-talpur)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-1B3A6B?style=for-the-badge&logo=google-chrome&logoColor=white)](https://uzaiftalpur.netlify.app)
[![Email](https://img.shields.io/badge/Email-Write-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:uzaiftalpur@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,100:1B3A6B&height=100&section=footer" width="100%"/>

*"A solution that stays in a thesis is not a solution."*

</div>
