# Medico-automatic-polyp-segmentation-challenge
The “Medico automatic polyp segmentation task” aims to develop computer-aided diagnosis systems for automatic polyp segmentation to detect all types of polyps (for example, irregular polyp, smaller or flat polyps) with high efficiency and accuracy. The main goal of the challenge is to benchmark semantic segmentation algorithms on a publicly available dataset, emphasizing robustness, speed, and generalization.

Participants will get access to a dataset consisting of 1,000 segmented polyp images from the gastrointestinal tract and a separate testing dataset. The challenge consists of two mandatory tasks, each focused on a different requirement for efficient polyp detection. We hope that this task encourages multimedia researchers to apply their vast knowledge to the medical field and make an impact that may affect real lives.

# Task Description
The participants are invited to submit the results on the following tasks:

1) Polyp segmentation task (required) - The polyp segmentation task asks participants to develop algorithms for segmenting polyps on a comprehensive dataset.

2) Algorithm efficiency task (required) - The algorithm efficiency task is similar to task one but puts a stronger emphasis on the algorithm’s speed in terms of frames-per-second. To ensure a fair evaluation, this task requires participants to submit a Docker image so that all algorithms are evaluated on the same hardware.

# Data
The dataset contains 1,000 polyp images and their corresponding ground truth mask. The datasets were collected from real routine clinical examinations at Vestre Viken Health Trust (VV) in Norway by expert gastroenterologists. The VV is the collaboration of the four hospitals that provide healthcare service to 470,000 peoples. The resolution of images varies from 332✕487 to 1920✕1072 pixels. Some of the images contain green thumbnail in the lower-left corner of the images showing the position marking from the ScopeGuide (Olympus). The training dataset can be downloaded from https://datasets.simula.no/kvasir-seg/.
