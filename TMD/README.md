DATASET : http://cs.unibo.it/projects/us-tm2017/


Architecture 1 : Fuse [Acc, Linear Acc and Gyr] [Rotation and Game rotation][Magnetic field and orientation]. and pass through random-forest classifier.

Architecture 2 : Fuse [Acc, Linear Acc] [Rotation and Game rotation][Magnetic field and orientation] and pass through random-forest classifier.

Architecture 3 : Fuse [Acc, Linear Acc] [Rotation and Game rotation]and pass through random-forest classifier.

### Navigating code:
 * The data is loaded and the null points are replaced with categorical mean values in Load_and_Visualise_Data.ipynb . It also contains the Correlation heatmaps.
 * The PPScore heatmaps are in relation_ppscore.ipynb
 * Respective fusions for given architecture are done in their respective jupyter notebooks
 * The classification is in RandomForestClassification.ipynb
