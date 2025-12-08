# Target_Dataset
Dataset Overview
The 3D point cloud data for each target distance were captured using the UTM-30LX-EW sensor. Depth measurements were processed with the URGBBENRI
Plus software. To ensure accurate measurement, the point clouds were preprocessed using pass-through filtering, outlier removal, and voxel grid
downsampling, with all parameters recorded in the rqt/ folder. Plane segmentation was applied to extract the target plane, followed by a min–max
bounding box computation and corner detection to determine the Height and Width.
Representative visualizations of Height and Width measurements are included in the figures/ folder.

#Data Access
The raw .pcd files and scripts are available upon request. Researchers can submit a request via the Google Form: [Insert Form Link].
Once your request is approved:
1. The requested files will be uploaded to the repository.
2. A direct GitHub link to the files will be shared with you via email.

#Reproducibility and Workflow
Software and Parameters: All preprocessing steps and filter parameters are documented in the rqt/ folder.
Pseudo Code: A simplified workflow is described below:

#Citation
Citation information will be provided after publication.
