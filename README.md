# Parallel-Structure-ShapeReconstruction

Created by C. Lv  from Shenzhen University. The paper is accepted by Multimedia tools and applications.

<img width="1357" alt="image" src="https://user-images.githubusercontent.com/65271555/232696591-dc0ba48b-c3aa-4646-ba2d-388ea5be4d9e.png">

## Introduction

Shape reconstruction from 3D point clouds is one of the most important topic in the field of computer graphics. In this paper, we propose a subdivision-based framework for this topic. The framework includes two parts: distance field optimization and mesh generation. The first part optimizes a point cloud into an approximately isotropic one based on a subdivision structure. The second part is to generate a triangular mesh from the optimized point cloud. The mesh is regarded as the result of shape reconstruction. The advantages of our method includes accurate geometric consistency, improved mesh quality, controllable point number, and fast speed. 

Using the .exe file, you can construct a mesh from a point cloud.

Using the .bat file, you can edit parameters for shape reconstruction.

Parameters:

Input filepath (.off .obj .ply); Simplification number; Output filepath (.obj).
