---
layout: about
title: About
permalink: /
subtitle: PhD Researcher at Your University

profile:
  align: right
  image: mi_foto.png
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div id="about"></div>

I am a researcher working on [your main research area](#), with a focus on practical and robust methods for real-world problems.

Previously, I completed my [Master's degree](#) at [institution](#), and my [Bachelor's degree](#) at [institution](#).

My interests include machine learning, applied mathematics, computer vision, and trustworthy AI.

<h2 id="projects" style="margin-top: 3.25rem">Projects</h2>

- [M2OLIE](#portfolio-m2olie) ("Mannheim Molecular Intervention Environment"). Project from the "Forschungscampus – öffentlich-private Partnerschaft für Innovationen" program, funded by the Federal Ministry of Research, Technology and Space (Bundesministerium für Forschung, Technologie und Raumfahrt).
- [FlyCAD](#portfolio-flycad) ("Flying Catheter Drive"). Funded by Invest BW from the Ministry of Economic Affairs, Labour and Tourism Baden-Württemberg (Ministerium für Wirtschaft, Arbeit und Tourismus Baden-Württemberg).
- [Ariadne](#portfolio-ariadne) ("A new approach for automated catheter control"). Project funded by the Heidelberg University Excellence Strategy (Field of Focus 2).
- [PeTRA](#portfolio-petra) ("Personen-Transfer Roboter-Assistent"). Funded by the Federal Ministry of Research, Technology and Space (Bundesministerium für Forschung, Technologie und Raumfahrt).
- [Mauer-Roboter 4.0](#portfolio-mauer-roboter-40). Collaborative project between the construction company Dressler GmbH, AAT Automation GmbH, and Hochschule Karlsruhe.
- [Avatera robotic surgery training system](#portfolio-avatera-robotic-surgery-training-system). Developed at ITK Engineering.
- [Final degree project in Electronic Engineering](#portfolio-final-degree-project-in-electronic-engineering). Completed at the National University of Mar del Plata (Universidad Nacional de Mar del Plata).

<h2 id="portfolio" style="margin-top: 3.25rem">Portfolio</h2>

<h3 id="portfolio-m2olie">M2OLIE</h3>
<p>M2OLIE (Mannheim Molecular Intervention Environment) is a long‑term, interdisciplinary research initiative funded by the German Federal Ministry of Education and Research. Its goal is to develop a new, efficient, and personalized cancer treatment process—especially for patients with oligometastatic cancer (a limited number of metastatic tumors).</p>

<p>The project aims to create a "closed loop" clinical process that integrates imaging, diagnostics, molecular analysis, and minimally invasive therapy into a continuous, data-driven workflow. This could allow cancer patients to go from admission to individualized treatment and discharge in a much shorter timeframe than current standard care.</p>

<p>This process works as follows:</p>

<ul>
  <li><strong>Patient Admission:</strong> Electronic patient file is created.</li>
  <li><strong>Imaging &amp; Biopsy:</strong> Precise imaging to locate tumors, followed by automated tissue sampling.</li>
  <li><strong>Analysis:</strong> Molecular analysis of the biopsy in the lab.</li>
  <li><strong>Therapy Decision:</strong> A digital expert system and an ad-hoc tumor board propose the individualized therapy.</li>
  <li><strong>Therapy:</strong> The minimally invasive treatment is performed.</li>
</ul>

<p>All steps are supported by a central "Data Lake" that stores and processes all information. The long-term vision is to establish an M²OLIE clinic and integrate this process into standard clinical practice.</p>

<p>Within the framework of this project, research has focused on the "Imaging &amp; Biopsy" step to precisely locate the tumor and extract its sample. This is achieved through innovations in tracking systems, patient registration, navigation systems, and robotic solutions. Some of the key research conducted is described below.</p>

<p>For more information visit: <a href="https://www.m2olie.de/" target="_blank" rel="noopener noreferrer">https://www.m2olie.de/</a></p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1518152006812-edab29b069ac?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="M2OLIE workflow architecture" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">M2OLIE - Workflow Architecture</h4>
              <p class="card-text">System-level architecture for image-guided molecular interventions across research and clinical environments.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Python</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Robotics</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Computer Vision</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Docker</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1579165466741-7f35e4755660?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="M2OLIE device integration" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">M2OLIE - Device Integration</h4>
              <p class="card-text">Integration of intervention hardware modules and synchronized control interfaces for reproducible procedures.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">C++</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Embedded Systems</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Qt</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1559757175-7cb057fba93f?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="M2OLIE planning algorithms" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">M2OLIE - Planning Algorithms</h4>
              <p class="card-text">Algorithmic support for trajectory planning and intervention strategy optimization under anatomical constraints.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Python</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">NumPy</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Optimization</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Jupyter</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="M2OLIE validation" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">M2OLIE - Validation and Benchmarking</h4>
              <p class="card-text">Experimental benchmarking and protocol validation to measure robustness, safety, and intervention performance.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Data Analysis</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Pandas</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Visualization</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">CI/CD</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<h3 id="portfolio-flycad">FlyCAD</h3>
<p>Comming soon</p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1579165466741-7f35e4755660?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="FlyCAD project" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">FlyCAD ("Flying Catheter Drive")</h4>
              <p class="card-text">Funded by Invest BW from the Ministry of Economic Affairs, Labour and Tourism Baden-Württemberg (Ministerium für Wirtschaft, Arbeit und Tourismus Baden-Württemberg).</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Matlab</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Embedded Systems</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Control</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">CAD</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<h3 id="portfolio-ariadne">Ariadne</h3>
<p>This project aimed to develop a novel system for the autonomous robotic navigation of guide wires during minimally invasive vascular procedures, such as angioplasty or aneurysm treatment. The primary goal was to significantly reduce complication rates—like perforations or dissections—caused by difficult wire navigation, especially in complex or tortuous vessels. The core challenge was the vast physiological variability of patient-specific vascular tissue, which makes accurate pre-operative modeling insufficient for safe real-time control. The project was funded by the Heidelberg University Excellence Strategy (Field of Focus 2).</p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="/assets/img/catheter_guido.png" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="Ariadne control strategy" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Ensemble Kalman inversion for image guided guide wire navigation in vascular systems</h4>
              <p class="card-text">Hanu, M., Hesser, J., Kanschat, G. et al. Ensemble Kalman inversion for image guided guide wire navigation in vascular systems. J.Math.Industry 14, 21 (2024).</p>
              <p class="card-text">This paper proposes the use of a technique called Ensemble Kalman Inversion (EKI) with subsampling to estimate unknown parameters, such as density and elasticity, of a guide wire used in cardiovascular interventions. The goal is to replicate high-resolution images of the wire using a physical model based on Cosserat rods. Since images generate large volumes of data, the standard method becomes computationally expensive, so the authors introduce a subsampling approach that processes only parts of the image in each iteration. Experiments with real data show that this variant achieves similar accuracy to the full method, but at a much lower cost, paving the way for more efficient and safer control of the guide wire in real procedures.</p>
              <p><strong>Contribution:</strong> development of the experimental setup</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://link.springer.com/article/10.1186/s13362-024-00159-4#citeas" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Python</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Control</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Simulation</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1581092921461-eab62e97a780?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="Ariadne sensor fusion" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Ariadne - Sensor Fusion</h4>
              <p class="card-text">Fusion of tracking and imaging signals to increase robustness of guidance and stability during intervention tasks.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">C++</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Sensor Fusion</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Kalman Filters</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Real-time</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="Ariadne experimental evaluation" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Ariadne - Experimental Evaluation</h4>
              <p class="card-text">Comprehensive testing on phantom scenarios to validate precision, repeatability, and operator-assist capabilities.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Benchmarking</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Data Analysis</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Visualization</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Reporting</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<h3 id="portfolio-petra">PeTRA</h3>
<p>PeTRA addresses safe robotic assistance for assisted transfer scenarios, with a strong emphasis on reliability and human-centered operation.</p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1581092921461-eab62e97a780?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="PeTRA project" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">PeTRA ("Personen-Transfer Roboter-Assistent")</h4>
              <p class="card-text">Funded by the Federal Ministry of Research, Technology and Space (Bundesministerium für Forschung, Technologie und Raumfahrt).</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Mechatronics</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Safety Systems</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Sensors</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Prototyping</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<h3 id="portfolio-mauer-roboter-40">Mauer-Roboter 4.0</h3>
<p>Mauer-Roboter 4.0 targets automation in construction through collaborative robotics and industrial integration in real building workflows.</p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1581092335397-9583eb92d232?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="Mauer-Roboter 4.0 project" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Mauer-Roboter 4.0</h4>
              <p class="card-text">Collaborative project between the construction company Dressler GmbH, AAT Automation GmbH, and Hochschule Karlsruhe.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Industrial Robotics</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Automation</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">PLC</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Field Testing</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<h3 id="portfolio-avatera-robotic-surgery-training-system">Avatera robotic surgery training system</h3>
<p>This project focuses on a robotic surgery training platform designed to improve usability, reproducibility, and surgeon learning workflows.</p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="Avatera robotic surgery training system" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Avatera robotic surgery training system</h4>
              <p class="card-text">Developed at ITK Engineering.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">C++</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Qt</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Medical Robotics</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">HMI</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<h3 id="portfolio-final-degree-project-in-electronic-engineering">Final degree project in Electronic Engineering</h3>
<p>Final undergraduate engineering work centered on the design, implementation, and validation of a complete electronic system.</p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=900&q=80" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="Final degree project in Electronic Engineering" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Final degree project in Electronic Engineering</h4>
              <p class="card-text">Completed at the National University of Mar del Plata (Universidad Nacional de Mar del Plata).</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://arxiv.org/" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Electronics</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">PCB Design</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Firmware</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Instrumentation</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
