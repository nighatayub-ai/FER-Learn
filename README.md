# FER-Learn: Facial Expression Recognition in Learning Environments

This repository complements the research study on facial expression recognition
(FER) for student affect analysis in real classroom environments, conducted at the
Department of Computer Science & IT, University of Malakand, Pakistan.

The work develops vision–language and adaptive deep-learning frameworks that
recognise six classroom-relevant affective states; engaged, bored, happy,
neutral, sad, and confused, from facial images captured in authentic
undergraduate classroom environment.

## Dataset Description

The curated classroom dataset consists of expert-annotated facial frames extracted
from continuous video recordings of real lectures. Frames were detected and cropped
using MTCNN, resized to 224×224 pixels, and annotated by a panel of three expert
psychologists via majority consensus. After quality filtering (removal of incorrect
face detections, blurred frames, and near-duplicate frames), high-quality images
were retained across the six affective states and partitioned at the subject and
session level to prevent identity, session, and frame-level leakage.

A small number of sample images are provided in the `samples/` folder for
illustration only. These samples are shared with the consent of the depicted
participants; they are a limited, representative subset and do not constitute the
full dataset.

## Dataset Availability

The full dataset is available from the corresponding author on request,
subject to the ethical-approval and participant-consent conditions under which the
data were collected. Because the data contain sensitive biometric information of
students, access is granted only for non-commercial academic research and under
appropriate data-protection terms.

## Ethical Statement

The data were collected following institutional ethical approval from the
Departmental (Computer Science & IT) Ethics Committee, University of Malakand, and
with the informed consent of all participants (and, where applicable, their parents
or guardians). The data are used solely for research on facial expression
recognition and are not used to grade, rank, or monitor individual students.

## Citation

If you use this repository or refer to this work, please cite:

> N. Ayub, F. Alam, A. Ullah, J. Ahmad, H. Farman, W. Shafai, and A. Sedik,
> "A Multimodal Vision–Language Framework using Contrastive Language-Image
> Pre-Training for Robust Facial Expression Analysis in Realistic Classroom
> Environments," Journal of King Saud University – Computer and Information
> Sciences, 2026.

## Contact

Nighat Ayub (PhD Scholar)
email: nighat.ayub@gmail.com
Department of Computer Science & IT, University of Malakand, Pakistan
Corresponding author: Dr. Fakhre Alam
email: fakhre@uom.edu.pk
Department of Computer Science & IT, University of Malakand, Pakistan
