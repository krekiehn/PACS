# PACS
Project to use AI/ML in clinical PACS

## Aim
Develop a (simple, docker based) IT infrastructure to make AI/ML tools (Python, Docker based) accessible/usable/executable via PACS (for non-clinical use aka shadow testing, "Shadow testing in the clinical environment").
1. Interface between the user's familiar IT environment/user interface (doctor, radiologist) and AI/ML tool (GPU server?!)
2. Simple addition/update of the AI/ML tools

## ToDo

1. Describe project idea
   - The overall goal?
     - Put AI to work in healthcare
     - Deployment of AI/ML Tools into clinical enviroment
     - Translation of knowledge into practice
   - Presentation?
   - Examples?
     - Which AI/ML Tools?
       - FDA approved?
       - Famous like Total Segmentator
       - Developed in-house
     - What do radiologists need in everyday clinical practice? Where can AI help? Save time?
       - Hospitating / Internship in radiology

3. Talk to People
   - [ ] Florian Becker
     - [ ] Grundidee
     - [ ] Forschungs PACS nutzen? 
   - [ ] Claus Glüer
     - [ ]  Grundidee
     - [ ] Resources?
   - [ ] Markus Both
     - [ ]  Grundidee
     - [ ]  Resources?
   - [ ] Olaf Jansen?
     - [ ] Support 
   - [ ] Eren Yilmaz
     - [ ] Coop?
   - [ ] Martin Götze
     - [ ] Docker Insides
     - [ ] Coop?
   - [ ] Christopher Hansen
     - [ ] Dental Clinic?
     - [ ] Coop?
   - [ ] Ronald Seidel
     - [ ] Coop?
   - [ ] Timo Damm
     - [ ] Coop?

3. Setting up a docker-based test environment
   - PACS
   - Server for AI/ML tool
   - Interaction between PACS and AI/ML tool
4. Implement a test enviroment in clinical setting
   - talkt to Florian Becker about using "Forschungs PACS"

5. Resources? Money?
 - WTSH / SH KI Sondervermögen
 - BMWi
 - BMBF
 - UKSH Grants?
 - DFG
 - NVidia/MONAI
 - Waterkant Coding Event

## Literature
<details>
<summary><h3>Paper:</h3></summary>
  
#### vastc
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10637622/
  - https://github.com/vastc/vastc/tree/master
#### Other
- https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7012173/
- https://medium.com/@hbjenssen/creating-a-segmentation-tool-that-radiologists-love-6e0a5de02f17

</details>

<details>
<summary><h3>Websites:</h3></summary>

#### PACS

##### **ORTHANC**
- **https://www.orthanc-server.com/download.php # ORTHANC**
  - https://discourse.orthanc-server.org/t/orthanc-docker-images-on-arm-64-architecture-solution-found/4084/4
  - https://www.web3.lu/orthanc-raspberry-pi/
  - https://medium.com/@elniak/orthanc-revolutionizing-medical-imaging-with-open-source-innovation-ffd07f385a14
  - https://github.com/orthanc-server
  - https://pypi.org/project/pyorthanc/
###### Docker
- http://192.168.178.64:8042/app/explorer.html
##### **DCM4CHE**
- **https://web.dcm4che.org/links  # DCM4CHE**
  - https://dcm4che.atlassian.net/wiki/spaces/d2/pages/1835025/dcmsnd
  - https://github.com/dcm4che/dcm4chee-arc-light/wiki/Run-minimum-set-of-archive-services-on-a-single-host
###### Docker
- https://192.168.178.64:8080/dcm4chee-arc
##### Alternative
- https://www.medfloss.org/taxonomy/term/84 # Collection of Open Source PACS
- https://image-systems.biz/products/free-dicom-pacs-tools/
- https://www.bmd-software.com/news/ai-segmentations-in-pacscenter-viewer/

#### DICOM
- **https://dicom.offis.de/dcmtk.php.en DCMTK**
  - https://support.dcmtk.org/docs/dcmsend.html 
- https://github.com/starviewer-medical/starviewer
</details>
