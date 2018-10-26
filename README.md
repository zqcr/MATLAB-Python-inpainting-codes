# MATLAB codes for the Image Inpainting Problem
This is a detailed MATLAB implementation of classic inpainting methods.

All the scripts provided are used in

```
Schoenlieb, Carola-Bibiane
Partial Differential Equation Methods for Image Inpainting.
Cambridge Monographs on Applied and Computational Mathematics,
Cambridge University Press, 2015
doi:10.1017/CBO9780511734304
```

Please use the following entry to cite this code:

```
@Misc{MATLABinpainting2016,
 author       = {Parisotto, Simone and Sch\"{o}nlieb, Carola},
 title        = {{MATLAB}/{Python} Codes for the {Image} {Inpainting} {Problem}},
 howpublished = {GitHub repository, {MATLAB} Central File Exchange},
 month        = {September},
 year         = {2016}
 }
```

<h4>1) Absolute Minimizing Lipschitz Extension Inpainting (AMLE)</h4>

Used to reproduce Figure 4.10 in the book. (Only grayscale images).

<img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/dataset/amle_clean.png"> <img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/results/amle_output.png"> 
      
**Bibliography**:
- Caselles, V., Morel, J. M., & Sbert, C. (1998). An axiomatic approach to image interpolation. Image Processing, IEEE Transactions on, 7(3), 376-386.
- Almansa, A. (2002). Echantillonnage, interpolation et detection: applications en imagerie satellitaire (Doctoral dissertation, Cachan, Ecole normale superieure).

<h4>2) Harmonic Inpainting</h4>

Used to reproduce Figure 2.2 in the book. This program solves harmonic inpainting via a discrete heat flow. (Both Grayscale / Color Images).

<img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/dataset/harmonic_input.png"> <img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/results/harmonic_output.png"> 

**Bibliography**:
- Shen, J., & Chan, T. F. (2002). Mathematical models for local nontexture inpaintings. SIAM Journal on Applied Mathematics, 62(3), 1019-1043.

<h4>3) Mumford-Shah Inpainting with Ambrosio-Tortorelli approximation</h4>

**Note**: Used to reproduce Figure 7.3 in the book.  (Both Grayscale / Color Images).

<img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/dataset/mumford_shah_input.png"  width=45%> <img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/results/mumford_shah_output.png"  width=45%> 

**Bibliography**: 
- Esedoglu, S., & Shen, J. (2002). Digital inpainting based on the Mumford-Shah-Euler image model. European Journal of Applied Mathematics, 13(04), 353-370.

<h4>4) Cahn-Hilliard Inpainting</h4>

Used to reproduce Figure 5.9 in the book.  (Both Grayscale / Color Images).

<img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/dataset/cahn_hilliard_input.png"> <img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/results/cahn_hilliard_output.png"> 

**Bibliography**: 
- Bertozzi, A., Esedoglu, S. & Gillette, A. (2007). Inpainting of binary images using the Cahn-Hilliard equation, IEEE Transactions on image processing 16.1 pp. 285-291 (2007).
- Schoenlieb, C.-B. & Bertozzi, A. (2011). Unconditionally stable schemes for higher order inpainting, Communications in Mathematical Sciences, Volume 9, Issue 2, pp. 413-457 (2011).

<h4>5) Transport Inpainting</h4>

Refer to Section 6.1 in the book. (Both Grayscale / Color Images).

<img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/dataset/transport_input.png"  width=45%> <img src="https://raw.githubusercontent.com/simoneparisotto/MATLAB-Python-inpainting-codes/master/results/transport_output.png" width=45%> 

**Bibliography**:
- Bertalmio, M. (2001). Processing of flat and non-flat image information on arbitrary manifolds using partial differential equations.PhD Thesis, 2001.

### License
[BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)
