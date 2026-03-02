---
layout: about
title: About
permalink: /
subtitle: PhD Candidate in Medical Technology | Bridging Research and Healthcare Innovation

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

I am a PhD candidate in Medical Technology at Heidelberg University, working at the Medical Faculty Mannheim on sensing and robotic systems for image-guided interventions.

From an early age, I’ve been drawn to creating technologies that improve people’s health and care. My work focuses on turning innovative research into practical medical solutions that are safe, reliable, and usable in real clinical settings.

I operate at the intersection of medical robotics, computer vision, and real-time control, collaborating closely with clinicians, interdisciplinary teams, and industry partners to bridge the gap between research and product development.

<strong>Key Expertise:</strong>

- Medical robotics & image-guided interventions
- Real-time control & perception pipelines
- System integration & clinical translation
- Hardware-software co-design & prototype deployment

<strong>Technical Skills:</strong>
C++, Python, ROS/ROS2, Optical Tracking, 3D Slicer, Embedded Systems, CAD, MATLAB, Unity 3D, FPGA/VHDL

<strong>Teaching</strong>

- Medical Physics (SS 2025, SS 2024). Medical Faculty Mannheim. Academic collaborator. Topics: Optics and radioactivity
- Supervision of various academic works (Master's theses, Bachelor's theses, internships and research). See projects for more details

<h2 id="contact" style="margin-top: 2rem">Contact</h2>

- Email: [Javier.Moviglia@medma.uni-heidelberg.de](mailto:Javier.Moviglia@medma.uni-heidelberg.de)
- LinkedIn: [linkedin.com/in/javiermoviglia](https://www.linkedin.com/in/javiermoviglia)

<h2 id="projects" style="margin-top: 3.25rem">Projects</h2>

- [M2OLIE](#portfolio-m2olie) ("Mannheim Molecular Intervention Environment"). Project from the "Forschungscampus – öffentlich-private Partnerschaft für Innovationen" program, funded by the Federal Ministry of Research, Technology and Space (Bundesministerium für Forschung, Technologie und Raumfahrt).
- [FlyCAD](#portfolio-flycad) ("Flying Catheter Drive"). Funded by Invest BW from the Ministry of Economic Affairs, Labour and Tourism Baden-Württemberg (Ministerium für Wirtschaft, Arbeit und Tourismus Baden-Württemberg).
- [Ariadne](#portfolio-ariadne) ("A new approach for automated catheter control"). Project funded by the Heidelberg University Excellence Strategy (Field of Focus 2).
- [PeTRA](#portfolio-petra) ("Personen-Transfer Roboter-Assistent"). Funded by the Federal Ministry of Research, Technology and Space (Bundesministerium für Forschung, Technologie und Raumfahrt).
- [Mauer-Roboter 4.0](#portfolio-mauer-roboter-40). Collaborative project between the construction company Dressler GmbH, AAT Automation GmbH, and Hochschule Karlsruhe.
- [Avatera robotic surgery training system](#portfolio-avatera-robotic-surgery-training-system). Developed at ITK Engineering.
- [Final degree project in Electronic Engineering](#portfolio-final-degree-project-in-electronic-engineering). Completed at the National University of Mar del Plata (Universidad Nacional de Mar del Plata).

<h2 id="portfolio" style="margin-top: 3.25rem">Portfolio | <a href="#contact">Contact</a></h2>

<h3 id="portfolio-m2olie">M2OLIE</h3>
<p><strong>Time period worked on the project:</strong> 05.2022 - today</p>
<p><strong>Place:</strong> Mannheim Institute for Intelligent Systems in Medicine (MIISM) at Medical Faculty Mannheim, Heidelberg University, Germany</p>
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

<p><strong>Activities:</strong> within the framework of this project, research has focused on the "Imaging &amp; Biopsy" step to precisely locate the tumor and extract its sample. This is achieved through innovations in tracking systems, patient registration, navigation systems, and robotic solutions. Some of the key research conducted is described below.</p>

<p>For more information visit: <a href="https://www.m2olie.de/" target="_blank" rel="noopener noreferrer">https://www.m2olie.de/</a></p>


<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="/assets/img/mono.gif" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="mono" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Monocular Near-Infrared Optical Tracking with Retroreflective Fiducial Markers for High-Accuracy Image-Guided Surgery</h4>
              <p class="card-text"><strong>Moviglia, J. H.</strong>, & Stallkamp, J. (2026). Monocular Near-Infrared Optical Tracking with Retroreflective Fiducial Markers for High-Accuracy Image-Guided Surgery. Sensors, 26(2), 357. https://doi.org/10.3390/s26020357</p>
              <p class="card-text">I developed a monocular near-infrared optical tracking system for image-guided surgery using compact dodecahedral retroreflective markers. I evaluated multiple fiducial families and hardware setups, identifying the ArUco MIP_36h12 markers as the most accurate, achieving 0.44 ± 0.20 mm translational error and 0.35 ± 0.16° rotational error at 30–70 cm. The system is compact, low-latency (32 ± 8 ms), CT/MRI-compatible, sterilizable, and suitable for integration into surgical navigation workflows.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://www.mdpi.com/1424-8220/26/2/357" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">C++</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Optics</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Computer Vision</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Docker</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Surgical Navigation</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Optical tracking</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">3D Printing</span>
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
            <img src="/assets/img/marco.png" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="mono" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Proof of concept of a novel tracking system with a monocular camera for image-guided surgery navigation</h4>
              <p class="card-text"><strong>Moviglia, J.</strong>, Dittmann, M., & Stallkamp, J. (2024). Proof of concept of a novel tracking system with a monocular camera for image-guided surgery navigation. Biomedical Engineering / Biomedizinische Technik. Advance online publication. https://doi.org/10.1515/bmt-2024-1002</p>
              <p class="card-text">We developed a novel monocular camera-based tracking system for image-guided surgery, building on the master thesis of Marco Dittmann, which i co-supervised with Prof. Dr. Stallkamp. Based on his results, we contributed to the adaptation and evaluation of the system, which uses a 5.1 MP monochrome monocular camera with a zoom lens and small plastic dodecahedral markers with ArUco patterns. We oversaw the testing of the optical hardware and tracking algorithm under varying lighting and depth conditions, achieving millimeter-level translational accuracy (~3 mm) and ~2° rotational accuracy over a 25 cm horizontal FOV. Our work included optimizing marker detection, dynamic zoom and focus adjustment, and assessing the system’s ergonomics and clinical suitability, while identifying limitations for real-time applications and guiding future improvements such as alternative lens technologies and lighting solutions.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://www.degruyterbrill.com/document/doi/10.1515/bmt-2024-1002/html" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">C++</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Optics</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Computer Vision</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Docker</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Surgical Navigation</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Optical tracking</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">3D Printing</span>
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
            <img src="/assets/img/registration.gif" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="mono" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Automated registration for interventional robotic systems</h4>
              <p class="card-text"><strong>Moviglia, J. H.</strong>, Dittmann, M., Siegfarth, M., Lutz, R., Iseke, N.-C., Sadi, F., & Stallkamp, J. (2023, October 19–20). Automated registration for interventional robotic systems. 6th Image-Guided Interventions Conference (IGIC), p. 60.</p>
              <p class="card-text">Three optical methods were developed for automatic patient registration without markers in CT-guided biopsies to reduce intervention time and radiation exposure. The approaches include a multi-stereo camera system for needle tracking, a 3D scanner using surface registration for higher precision, and a time-of-flight camera combined with a monocular camera to track needle position and detect patient surface deformation due to respiration. Experimental results showed millimeter-level accuracy, with the 3D scanner achieving the highest precision, while the time-of-flight approach appears most promising for dynamic tracking and future tumor localization.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://www.igic.de/igic_media/Data/Book+of+Abstracts+IGIC+2023.pdf" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Monocular camera</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">3D Scanner</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">ToF camera</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Optics</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Surgical navigation</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Surface registration</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Optical tracking</span>
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
            <img src="/assets/img/hno.png" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="mono" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Entwicklung und Evaluation einer Ultraschallnavigation für Freihandbiopsien kleiner Raumforderungen im Kopf-Hals-Bereich</h4>
              <p class="card-text">Scherl, C., Otto, M., Ghanem, I., <strong>Moviglia, J.</strong>, Sadi, F., Gnilka, T., Rotter, N., Zaubitzer, L., Stallkamp, J. Entwicklung und Evaluation einer Ultraschallnavigation für Freihandbiopsien kleiner Raumforderungen im Kopf-Hals-Bereich. HNO 72, 76–82 (2024). https://doi.org/10.1007/s00106-023-01385-9</p>
              <p class="card-text">The study aimed to develop and evaluate a new ultrasound‑controlled navigation system for free‑hand biopsies of small target structures in the head and neck area. The authors constructed a neck phantom with sonographically detectable masses and used a deep neural network for automatic segmentation. Using an individually designed tracking tool attached to the ultrasound scanner, they recorded the positions of the ultrasound device, target masses, and biopsy needle in a world coordinate system. In most tests, the system successfully guided the needle to the target with an average deviation of about 2.5 mm, and auditory feedback was used to assist navigation. The approach offers advantages over conventional navigation systems, including real‑time automatic registration without preoperative imaging, maintenance of the surgeon’s optical axis, and hands‑free operation during biopsy.</p>
              <p><strong>Contribution:</strong> development of the experimental setup; Intercommunication between the ultrasound and the optical tracking system with the control and processing system.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://link.springer.com/article/10.1007/s00106-023-01385-9" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-dark mr-1 mb-1">Python</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Ultrasound</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Optical tracking</span>
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
            <img src="/assets/img/intro.png" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="mono" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">A semi-automated robotic system for percutaneous interventions</h4>
              <p class="card-text">Siegfarth, M., Lutz, R., Iseke, N.-C., <strong>Moviglia, J.</strong>, Sadi, F., Stallkamp, J. A semi-automated robotic system for percutaneous interventions. Int J CARS 18, 1571–1575 (2023). https://doi.org/10.1007/s11548-023-02882-6</p>
              <p class="card-text">The paper presents a hybrid semi‑automated robotic assistive device designed to support needle‑based percutaneous interventions within the limited space of a CT scanner gantry. The system combines manual rough positioning with robotic fine positioning and an optical tracking unit for needle guidance, using open‑source software including ROS2, MoveIt2, and 3D Slicer. Initial tests with a clinical CT scanner showed that the system’s hardware and software components could communicate and operate as intended; needle placements exhibited deviations primarily due to encoder inaccuracies, while the optical tracker yielded a mean positioning deviation of about 3.9 mm. The first validation confirmed feasibility, and future integration of automatic position correction using optical tracking is expected to improve accuracy significantly.</p>
              <p><strong>Contribution:</strong> Development of the multi-stereo optical tracking system, integration of 3D Slicer into ROS as the navigation system platform, and collaboration on the robot’s software architecture.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://link.springer.com/article/10.1007/s11548-023-02882-6" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-dark mr-1 mb-1">Python</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">3D Slicer</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Optical tracking</span>
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
<p><strong>Time period worked on the project:</strong> 02.2025 - 09.2025</p>
<p><strong>Place:</strong> Mannheim Institute for Intelligent Systems in Medicine (MIISM) at Medical Faculty Mannheim, Heidelberg University, Germany</p>
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
              <p class="card-text">Comming soon.</p>
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
<p><strong>Time period worked on the project:</strong> 05.2022 - 12.2023</p>
<p><strong>Place:</strong> Mannheim Institute for Intelligent Systems in Medicine (MIISM) at Medical Faculty Mannheim, Heidelberg University, Germany</p>
<p>This project aimed to develop a novel system for the autonomous robotic navigation of guide wires during minimally invasive vascular procedures, such as angioplasty or aneurysm treatment. The primary goal was to significantly reduce complication rates—like perforations or dissections—caused by difficult wire navigation, especially in complex or tortuous vessels. The core challenge was the vast physiological variability of patient-specific vascular tissue, which makes accurate pre-operative modeling insufficient for safe real-time control. The project was funded by the Heidelberg University Excellence Strategy (Field of Focus 2).</p>
<p><strong>Activities:</strong> the guide wire actuation system was designed with computer-based control using ROS, and different mechanisms for measuring guide wire force, both distal and proximal, were investigated in order to use this information as haptic feedback.</p>
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
              <p class="card-text">Hanu, M., Hesser, J., Kanschat, G., <strong>Moviglia, J.</strong>, Schillings, C., & Stallkamp, J. Ensemble Kalman inversion for image guided guide wire navigation in vascular systems. J.Math.Industry 14, 21 (2024). https://doi.org/10.1186/s13362-024-00159-4 </p>
              <p class="card-text">This paper proposes the use of a technique called Ensemble Kalman Inversion (EKI) with subsampling to estimate unknown parameters, such as density and elasticity, of a guide wire used in cardiovascular interventions. The goal is to replicate high-resolution images of the wire using a physical model based on Cosserat rods. Since images generate large volumes of data, the standard method becomes computationally expensive, so the authors introduce a subsampling approach that processes only parts of the image in each iteration. Experiments with real data show that this variant achieves similar accuracy to the full method, but at a much lower cost, paving the way for more efficient and safer control of the guide wire in real procedures.</p>
              <p><strong>Contribution:</strong> development of the experimental setup</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://link.springer.com/article/10.1186/s13362-024-00159-4#citeas" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Python</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Embedded Systems</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Control</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">CAD</span>
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
            <img src="/assets/img/fbg.png" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="Ariadne force feedback system" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">FBG-Based Distal Force Sensor to Improve Remote Catheter Procedures</h4>
              <p class="card-text"><strong>J. H. Moviglia Parra</strong>, A. Hegel, and J. Stallkamp, “FBG-based distal force sensor to improve remote catheter procedures,” 7th Image-Guided Interventions Conference, Magdeburg, Germany, Oct. 23–24, 2025, pp. 49–50.</p>
              <p class="card-text">FBG-based distal force sensors were developed for fiber-optic guidewires to provide real-time, temperature-compensated feedback during minimally invasive catheterizations. Integrated into a remote system, they improved control, safety, and precision, addressing the lack of tactile information at the guidewire tip. Future work will focus on multi-axis sensing, miniaturization, and clinical validation.</p>
              <p><strong>Contribution:</strong> Management and supervision of A. Hegel’s master’s thesis; writing of abstract</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://www.igic.de/igic_media/Data/Book+of+Abstracts+IGIC+2025.pdf" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Python</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Fiber optic</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Haptic Feedback</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Embedded Systems</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>




  </div>
</div>

<h3 id="portfolio-petra">PeTRA</h3>
<p><strong>Time period worked on the project:</strong> 12.2020 - 04.2022</p>
<p><strong>Place:</strong> Institute for Robotics and Autonomous Systems (IRAS) at Hochschule Karlsruhe, Germany</p>
<p>The PeTRA (Person Transfer Robot Assistant) project, developed by the Hochschule Karlsruhe, aimed to create a robotic assistant that helped transport and accompany patients safely within hospitals or healthcare facilities. Its goal was to reduce the workload of healthcare staff, improve the efficiency of hospital processes, and increase patients’ autonomy and safety during their movements between different areas.</p>
<p><strong>Activities:</strong> the research focused on the development of the robot’s navigation algorithm with a trailer attached for transport, using the ROS Navigation Stack and its integration into the software architecture through behavior trees. Work was also carried out jointly with the industrial partner KUKA for its integration.</p>
<p>For more information visit: <a href="http://patiententransportassistent.de/" target="_blank" rel="noopener noreferrer">http://patiententransportassistent.de/</a></p>

<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="/assets/img/petra.png" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="petra" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Softwareentwicklung des Personen-Transfer Roboter-Assistenten (PeTRA) zur Unterstützung von Pflegekräften</h4>
              <p class="card-text">A. Zachariae, C. Wurll, M. Weisenböhler, and <strong>J. Moviglia</strong>, “Softwareentwicklung des Personen-Transfer Roboter-Assistenten (PeTRA) zur Unterstützung von Pflegekräften,” in 4. Clusterkonferenz „Zukunft der Pflege“, Hannover, Feb. 2022, pp. 51–52.</p>
              <p class="card-text">The PeTRA project aims to reduce the workload of healthcare staff by automating patient transport, allowing more time for quality care while promoting patient mobility and autonomy. At Hochschule Karlsruhe, software was developed using ROS 2 to manage workflow, monitor patients, and facilitate communication. The system coordinates transport via behavior trees, supports multiple mobility modes, and enables human-machine interaction through voice commands, multilingual speech output, and a tablet interface. Patient safety is ensured through real-time monitoring with a 3D depth camera and neural network for pose detection, allowing immediate assistance in case of falls, fainting, or other risks</p>
              <p><strong>Contribution:</strong> Navigation and integration in the software architecture</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://ppz-hannover.de/wp-content/uploads/2024/10/CZP2021_Konferenzband.pdf" target="_blank" rel="noopener noreferrer">Paper</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Robotic</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">ROS</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Navigation</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Software architecture</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<h3 id="portfolio-mauer-roboter-40">Mauer-Roboter 4.0</h3>
<p><strong>Time period worked on the project:</strong> 02.2021 - 04.2022</p>
<p><strong>Place:</strong> Institute for Robotics and Autonomous Systems (IRAS) at Hochschule Karlsruhe, Germany</p>
<p>In collaboration with the companies Dressler GmbH and AAT Automation GmbH, a mobile robot was developed at the Institute for Robotics and Autonomous Systems (IRAS) at Hochschule Karlsruhe with the aim of automating the construction of sand-lime brick walls on construction sites.</p>
<p><strong>Activities:</strong> Project management, communication with partners, and supervision of several student projects that contributed to the construction of the robot. Among the technical activities carried out with students were the installation of the KUKA robotic arm in the institute’s facilities, the robot safety cage with integrated sensors and PLC control (Programmable Logic Controller), programming of the EKI code interface with ROS, development of a mobile platform position measurement system using integrated sensors and an external tracking system, implementation of pick-and-place operations with computer vision algorithms, and market studies.</p>
<p>For more information visit: <a href="https://www.h-ka.de/iras/profil/news-detailseite/artikel/mauer-roboter-40" target="_blank" rel="noopener noreferrer">https://www.h-ka.de/iras/profil/news-detailseite/artikel/mauer-roboter-40</a></p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="/assets/img/maurob.png" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="maurob" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Mauer-Roboter 4.0</h4>
              <p class="card-text">Collaborative project between the construction company Dressler GmbH, AAT Automation GmbH, and Hochschule Karlsruhe.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://www.h-ka.de/iras/profil/news-detailseite/artikel/mauer-roboter-40" target="_blank" rel="noopener noreferrer">Web</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Management</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Robotic</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Computer vision</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Navigation</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Pick and Place</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<h3 id="portfolio-avatera-robotic-surgery-training-system">Avatera robotic surgery training system</h3>
<p><strong>Time period worked on the project:</strong> 03.2019 - 08.2019</p>
<p><strong>Place:</strong> ITK Engineering GmbH, Rülzheim, Germany</p>
<p>The project consisted of the development of the Avatera robotic training simulator.</p>
<p><strong>Activities:</strong> programming VR (virtual reality) exercises with Unity 3D for the training simulator, hardware configuration, programming the interface with Qt, research on realistic tissue cross-section representation, and collaborative work using Git.</p>
<p>For more information visit: </p>
<p><a href="https://www.itk-engineering.de/" target="_blank" rel="noopener noreferrer">https://www.itk-engineering.de/</a></p>
<p><a href="https://avatera.eu/avatera-system" target="_blank" rel="noopener noreferrer">https://avatera.eu/avatera-system</a></p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="/assets/img/avatera.png" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="avatera" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Avatera robotic surgery training system</h4>
              <p class="card-text">Developed at ITK Engineering GmbH.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://avatera.eu/avatera-system" target="_blank" rel="noopener noreferrer">Web</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">C#</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">Qt</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Medical Simulator</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Unity 3D</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">git</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<h3 id="portfolio-final-degree-project-in-electronic-engineering">Final degree project in Electronic Engineering</h3>
<p><strong>Time period worked on the project:</strong> 2019 - 08.2020</p>
<p><strong>Place:</strong> Instrumentation and Control Laboratory. Department of Electronics, Faculty of Engineering, National University of Mar del Plata. Argentina</p>
<p>In my thesis, I worked on interleaved DC/DC converters, which efficiently control high currents by splitting them across multiple phases. I focused on mitigating the effects of phase inductor imbalances, which increase total current ripple (∆iₜ) and lower-frequency harmonics. Following the method proposed by Antoszczuk et al., I implemented an optimal phase ordering using genetic algorithms to minimize ripple amplitude. My work included developing signal acquisition hardware, designing a digital platform on an FPGA in VHDL, and validating the implementation through simulations and experimental tests. This project was carried out at the Instrumentation and Control Laboratory of the National University of Mar del Plata (UNMdP), which collaborates closely with CERN (European Organization for Nuclear Research), and it is one of several projects that emerged from these collaborative efforts.</p>
<div class="projects">
  <div class="row row-cols-1">
    <div class="col mb-4">
      <div class="card h-100 hoverable">
        <div class="row no-gutters align-items-stretch">
          <div class="col-md-4">
            <img src="/assets/img/final.png" class="img-fluid w-100 border rounded p-2" style="aspect-ratio: 1 / 1; object-fit: contain" alt="final" loading="lazy">
          </div>
          <div class="col-md-8">
            <div class="card-body">
              <h4 class="card-title">Ordenamiento óptimo de las fases de un convertidor multifásico de potencia mediante FPGA</h4>
              <p class="card-text"><strong>J. H. Moviglia</strong>, Ordenamiento óptimo de las fases de un convertidor multifásico de potencia mediante FPGA, Undergraduate thesis, Faculty of Engineering, National University of Mar del Plata, Argentina, Aug. 2020.</p>
              <p>
                <a class="btn btn-sm btn-outline-primary" href="https://rinfi.fi.mdp.edu.ar/bitstream/handle/123456789/426/Moviglia-TFG-IEe-2020.pdf?sequence=1&isAllowed=y" target="_blank" rel="noopener noreferrer">pdf</a>
              </p>
              <p class="mb-1"><strong>Tech stack</strong></p>
              <div class="mb-0">
                <span class="badge badge-pill badge-primary mr-1 mb-1">Electronics</span>
                <span class="badge badge-pill badge-info mr-1 mb-1">PCB Design</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">FPGA</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">VHDL</span>
                <span class="badge badge-pill badge-secondary mr-1 mb-1">Matlab</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">AI</span>
                <span class="badge badge-pill badge-dark mr-1 mb-1">Simulation</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
