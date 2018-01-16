#### 1. DV1542 Demo
This was a project for a course in 3D programming. It is a 3d rendering engine with the purpose to learn about different techniques used in games and other 3d applications. I choose to implement the following techniques in a space setting. Its implemented as 3 different rooms connected by corridors. Each room is designed to demonstrate a set of techniques.

[![](dv1542_preview.png)](dv1542_preview.png)

**Room 1** have a single point light in the middle, and spheres that move around the room. The spheres cast a shadow on each others and the walls.

**Room 2** is a pool with simulated water waves. The waves are simulated as a sum of sin waves in a compute program running on the GPU.

**Room 3** in this room I've placed a GPU driven particle system each particle is driven by a simple rule - accelerate towards several attractor points, as a single particle its not so impressive, but since they are driven by the GPU, I can have thousands, up to around 2-3 million particles alive at any one time.

### [More info + images](dv1542/index.md)

-------------------------------------------

#### 2. Volume
This is part of another project but is worth showing of by its self. Its a project to implementing different algorithms for generating [implicit surfaces](https://en.wikipedia.org/wiki/Implicit_surface). Currently I have implemented the following algorithms:
* **Marching Cubes** _(W. E. Lorensen and H. E. Cline)_
* **Dual Contouring Marching Cubes** _(by Scott Schaefer and Joe Warren)_
* **Dual Contouring** _(by Tao Ju, Frank Lossaso, Scott Schaefer and Joe Warren)_
* **Adoptive Dual Contouring** _(using the adoptive nature of DCMC with Dual Contouring)_

In the future I would also like to implement the following algorithms:
* **Surface Nets** _(by Sarah F. F. Gibson)_
* **Dual Marching Cubes** _(by Gregory M. Nielson)_
* **Manifold Dual Contouring** _(by Scott Schaefer, Tao Ju and Joe Warren)_

### [More information & images of the different algorithms](volume/index.md)

#### 3. Meta-ball raytracer in JavaScript+WebGL

-------------------------------------------
