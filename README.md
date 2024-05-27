# LFD
Leaf chlorophyll Fluorescence with Dorsiventrality


### A leaf-level radiative transfer model for simulating fluorescence with dorsiventrality considered.

### 1. Leaf dorsiventrality 

* _r-t dorsinvetrality_: differences in reflectance/transmittance between adaxial and abaxial leaf surfaces

* _f dorsinvetrality_: differences in emitted fluorescence when adaxial and abaxial leaf surfaces are illuminated

### 2. Input

```
$C_{ab}$: Total chlorophyll content                       
$C_{ar}$: Total carotenoid content                        
$C_{anth}$: Total anthocyanins content                      
$C_{brown}$: Total brown pigments                            
$C_{w}$: Total water content                             
$C_{m}$: Total dry matter content                        
$C_{x}$: Photochemical reflectance parameter             
N: Leaf structure parameter                        
$p$: Fraction of N in palisade                       
$d$: Fraction of $C_{ab}$ ($C_{ar}$) in palisade
$r_1^b$: Bottom-side reflectance of upper epidermis      
$a_1$: Ratio of $r_1^t$ to $r_1^b$                             
$r_4^t$: Top-side reflectance of lower epidermis         
$a_4$: Ratio of $r_4^b$ to $r_4^t$                             
${\eta}_\mathrm{I}^2$: FQE for PS-I in palisade                        
${\eta}_\mathrm{II}^2$: FQE for PS-II in palisade                       
${\eta}_\mathrm{I}^3$: FQE for PS-I in spongy                          
${\eta}_\mathrm{II}^3$: FQE for PS-II in spongy                         
```


### 3. Output

* LRT
```
LRT(1): adaxial reflectance ($R^t$)
LRT(2): adaxial transmittance ($T^t$)
LRT(3): abaxial reflectance ($R^b$)
LRT(4): abaxial transmittance ($T^b$)
```

* FLUO_I
```
FLUO_I(1): forward PS-I fluoresence matrix for adaxial illumination ($M_f^t$)
FLUO_I(2): backward PS-I fluoresence matrix for adaxial illumination ($M_b^t$)
FLUO_I(3): forward PS-I fluoresence matrix for abaxial illumination ($M_f^b$)
FLUO_I(4): backward PS-I fluoresence matrix for abaxial illumination ($M_b^b$)
```

* FLUO_II
```
FLUO_II(1): forward PS-II fluoresence matrix for adaxial illumination ($M_f^t$)
FLUO_II(2): backward PS-II fluoresence matrix for adaxial illumination ($M_b^t$)
FLUO_II(3): forward PS-II fluoresence matrix for abaxial illumination ($M_f^b$)
FLUO_II(4): backward PS-II fluoresence matrix for abaxial illumination ($M_b^b$)
```

### 4. Citation

* Shi H. (2024). Exploring vegetation chlorophyll fluorescence with leaf dorsiventrality. (under review)
* Shi H., Xiao Z. (2022). A Canopy Radiative Transfer Model Considering Leaf Dorsoventrality. IEEE Trans. Geosci. Remote Sens. 60, 2002711. https://doi.org/10.1109/TGRS.2021.3119315
