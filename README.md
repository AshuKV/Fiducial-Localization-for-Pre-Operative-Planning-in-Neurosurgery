# Fiducial-Localization-for-Pre-Operative-Planning-in-Neurosurgery

## Organization	
Department of Atomic Energy

## Problem Statement	
Preoperative planning is a phase before actual surgery procedure in which the surgeon can take all the time needed to define the surgical problem, to identify fully all the anatomical and technical aspects of the procedure, and then carefully plan the solution. In order to facilitate this, the patient is assumed to be located in a coordinate system refered to as the ‘Patient Coordinate System’(PCS), whereas the surgeon has access to pre-operative medical scans(like CT/MRI etc.) of the subject in the coordinate system refered to as the ‘Image Coordinate System’(ICS). Any procedure planned in medical scans under ICS can be transfered to patient domain by utilizing this mapping. The challenge of accurately establishing this mapping (or registration) between PCS and ICS plays a critical role in influencing the reliability of the surgery procedure itself. Currently accepted practice involves the use of special markers called the ‘fiducials’ for the purpose of estimating PCS-to-ICS mapping. Apart from establishing correspondances between the appearance of fiducials in both patient and image coordinate systems, autonomas and accurate localization of these markers in image coordinate system is an open-challenge. Currently, surgeons manually annotate and localize these fiducials or utilize semi-automatic tools provided by their treatment planning suite. The goal of this challenge is therefore, to develop fully autonomas algorithm for detection and localization of fiducials in pre-operative scans. Concretely, the participants will be provided with MRI head-scans with fiducials affixed on the skull surface and the task will be to estimate 3D coordinates of the center of these fiducials with respect to the image coordinate system. Accruacy of their algorithm will be tested on the corresponding ground-truth values and generalization will be evaluated based on unseen test data.

## Category	
Software

## PS Number 
PC86

## 	Domain Bucket
Healthcare & Biomedical Devices
