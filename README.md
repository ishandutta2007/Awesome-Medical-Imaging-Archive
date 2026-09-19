# Awesome-Medical-Imaging-Archive

## Top Medical Imaging Archive (PACS Cloud) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Cloud PACS, VNA, DICOM Archive, Image Exchange, Diagnostic Viewing & Enterprise Imaging*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Medical Imaging Archives (Cloud PACS / VNA)**. These systems store, manage, distribute, and display DICOM medical images—supporting diagnostic reading, image exchange, and enterprise imaging workflows in the cloud or hybrid environments.

**Examples** include Ambra Health, Life Image, Change Healthcare PACS, Philips Vue PACS, GE Centricity PACS, Visage Imaging, Fujifilm Synapse, Merge PACS, Intelerad, and MedDream (the category leaders).

**Open-source emphasis**: Medical imaging has a mature open-source stack. **Orthanc**, **dcm4chee**, and the **OHIF Viewer** form a widely deployed, production-capable open PACS and viewing ecosystem. Additional tools support DICOM routing, web viewing, and research archives. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Ambra Health (Intelerad)](https://ambrahealth.com/)**  
  Cloud-native medical image management and exchange platform widely used for sharing studies across institutions and enabling cloud PACS workflows.

- **[Life Image](https://www.lifeimage.com/)**  
  Image exchange and network platform connecting providers for sharing medical images and reports across health systems.

- **[Change Healthcare PACS](https://www.changehealthcare.com/)**  
  Enterprise imaging and PACS solutions (historically part of Change Healthcare’s imaging portfolio) for hospital and outpatient settings.

- **[Philips Vue PACS](https://www.philips.com/)**  
  Enterprise PACS and imaging informatics platform from Philips supporting diagnostic workflows and enterprise image management.

- **[GE Centricity PACS / GE HealthCare Imaging](https://www.gehealthcare.com/)**  
  Long-standing PACS and enterprise imaging offerings from GE HealthCare for radiology and multi-department imaging.

- **[Visage Imaging](https://visageimaging.com/)**  
  Server-side rendering enterprise imaging platform known for speed and cloud-enabled diagnostic viewing at scale.

- **[Fujifilm Synapse](https://www.fujifilm.com/)**  
  Enterprise imaging and PACS/VNA platform with strong multi-department (radiology, cardiology, pathology) capabilities.

- **[Merge PACS (Merative / IBM Watson Health heritage)](https://www.merative.com/)**  
  PACS and imaging solutions historically associated with Merge Healthcare, used in diagnostic imaging environments.

- **[Intelerad](https://www.intelerad.com/)**  
  Medical imaging platform provider (including IntelePACS and cloud offerings) focused on radiology and ambulatory imaging workflows; increasingly integrated with broader GE HealthCare portfolio.

- **[MedDream](https://www.softneta.com/)**  
  Web-based DICOM viewer and PACS components often deployed for diagnostic and clinical viewing, including cloud-friendly setups.

## Open-Source GitHub Projects
- **[Orthanc](https://www.orthanc-server.com/)**  
  Lightweight, open-source DICOM server / PACS widely used for archives, research, teleradiology, and as a building block for cloud and hybrid imaging systems.

- **[dcm4che / dcm4chee-arc-light](https://github.com/dcm4che)**  
  Comprehensive open-source DICOM toolkit and archive (PACS) implementing DICOM, HL7, and DICOMweb services for enterprise-grade imaging archives.

- **[OHIF Viewer](https://github.com/OHIF/Viewers)**  
  Leading open-source, zero-footprint web DICOM viewer used worldwide for diagnostic and clinical image display, often paired with Orthanc or dcm4chee.

- **[Orthanc ecosystem plugins and tools](https://github.com/orthanc-server)**  
  Rich set of plugins (DICOMweb, PostgreSQL, authorization, whole-slide imaging, etc.) that extend Orthanc into full imaging solutions.

- **[Weasis](https://github.com/nroduit/Weasis)**  
  Open-source multipurpose DICOM viewer for desktop and web, supporting diagnostic-quality display and advanced tools.

- **[DVTk and DICOM validation open tools](https://github.com/)**  
  Open utilities for testing and validating DICOM connectivity and conformance.

- **[DICOMweb open clients and servers](https://github.com/)**  
  Libraries implementing DICOMweb (QIDO, WADO, STOW) for modern web-based imaging integration.

- **[Research PACS and anonymization open pipelines](https://github.com/)**  
  Tools for de-identification, research archives, and secondary use of imaging data under ethical controls.

- **[3D Slicer and open imaging analysis](https://github.com/Slicer)**  
  Open-source platform for medical image computing, visualization, and research analysis often used alongside PACS archives.

- **[Secure OHIF + Orthanc deployment examples](https://github.com/)**  
  Community reference architectures combining OHIF Viewer with Orthanc behind OpenID/SSO for production-like security.

### Additional Strong Open-Source Options
- Deploying **Orthanc + OHIF** as a lightweight, modern cloud or on-prem PACS and viewer stack.
- Using **dcm4chee-arc-light** when a fuller enterprise archive with HL7 and advanced DICOM services is required.
- Combining open archives with commercial viewers or vice versa in hybrid architectures.
- Accepting that large-scale enterprise imaging, vendor-neutral archives at health-system scale, advanced workflow orchestration, and turnkey support still favor commercial platforms (Ambra/Intelerad, Visage, Fujifilm Synapse, Philips, GE, etc.).
- Focusing open-source efforts on cost control, research imaging, teleradiology, and avoiding lock-in for departmental or specialty archives.

**Frameworks for building custom systems**: Store studies in Orthanc or dcm4chee → expose DICOMweb → view with OHIF or Weasis → route and share via secure web portals → integrate with EMR via HL7/FHIR. Suitable for clinics, research centers, and health systems with imaging IT expertise. Many hospitals still standardize on commercial cloud PACS/VNA platforms for enterprise support and regulatory confidence.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Medical imaging systems handle protected health information (PHI) and are subject to HIPAA, GDPR, and medical-device/regulatory requirements in many jurisdictions. Open-source PACS deployments require hardened security, access controls, audit logging, backup, and clinical validation before diagnostic use. This list is not clinical, legal, or regulatory advice. Incorrect configuration can create serious patient-safety and privacy risks.

---
**Made for radiology IT, imaging informatics, and healthcare technology teams.**
Let's keep medical imaging interoperable, accessible, and as open as practical.
