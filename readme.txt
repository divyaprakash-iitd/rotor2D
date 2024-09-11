-----------------------------------------------------------------------------------------
The case files were created for OpenFOAM-v2012
-----------------------------------------------------------------------------------------

To run the simulation, one can simply run the command pimpleFoam in the cavity directory, 
since the mesh files are already copied to the simulation directory.


To make changes to the mesh, 
1. Navigate to the snappy directory.
2. Edit the blockMeshDict or snappyHexMeshDict as required
3. Run blockMesh
4. Run snappyHexMesh -overwrite
5. Run creatPatch -overwrite
6. Copy the snappy/constant/polymesh directory to cavity/constant directory


For any queries, you can mail to divyaprakash.poddar@gmail.com

Author: Divyaprakash
Email: divyaprakash.poddar@gmail.com
Date: 11/9/2024

