# LFD
Leaf chlorophyll Fluorescence with Dorsiventrality


### A leaf-level radiative transfer model for simulating fluorescence with dorsiventrality considered.

### 1. Leaf dorsiventrality 

* _r-t dorsinvetrality_: differences in reflectance/transmittance between adaxial and abaxial leaf surfaces

* _f dorsinvetrality_: differences in emitted fluorescence when adaxial and abaxial leaf surfaces are illuminated

### 2. Input

| Parameter              | Description                                 | Unit                       |
| ---------------------- | ------------------------------------------- | -------------------------- |
| $C_{ab}$               | Total chlorophyll content                   | $\mathrm{ {\mu}g / cm^2 }$ |
| $C_{ar}$               | Total carotenoid content                    | $\mathrm{ {\mu}g / cm^2 }$ |
| $C_{anth}$             | Total anthocyanins content                  | $\mathrm{ {\mu}g / cm^2 }$ |
| $C_{brown}$            | Total brown pigments                        | -                          |
| $C_{w}$                | Total water content                         | $\mathrm{ g / cm^2} $      |
| $C_{m}$                | Total dry matter content                    | $\mathrm{ g / cm^2} $      |
| $C_{x}$                | Photochemical reflectance parameter         | -                          |
| $\mathrm{N}$           | Leaf structure parameter                    | -                          |
| $p$                    | Fraction of N in palisade                   | -                          |
| $d$                    | Fraction of $C_{ab}$ ($C_{ar}$) in palisade | -                          |
| $r_1^b$                | Bottom-side reflectance of upper epidermis  | -                          |
| $a_1$                  | Ratio of $r_1^t$ to $r_1^b$                 | -                          |
| $r_4^t$                | Top-side reflectance of lower epidermis     | -                          |
| $a_4$                  | Ratio of $r_4^b$ to $r_4^t$                 | -                          |
| ${\eta}_\mathrm{I}^2$  | FQE for PS-I in palisade                    | -                          |
| ${\eta}_\mathrm{II}^2$ | FQE for PS-II in palisade                   | -                          |
| ${\eta}_\mathrm{I}^3$  | FQE for PS-I in spongy                      | -                          |
| ${\eta}_\mathrm{II}^3$ | FQE for PS-II in spongy                     | -                          |

### 3. Output

|            | Parameter | Description                                                |
| ---------- | --------- | ---------------------------------------------------------- |
| LRT(1)     |$R^t$      | Adaxial reflectance                                        |
| LRT(2)     |$T^t$      | Adaxial transmittance                                      |
| LRT(3)     |$R^b$      | Abaxial reflectance                                        |
| LRT(4)     |$T^b$      | Abaxial transmittance                                      |
| FLUO_I(1)  |$M_f^t$    | Forward PS-I fluoresence matrix for adaxial illumination   |
| FLUO_I(2)  |$M_b^t$    | Backward PS-I fluoresence matrix for adaxial illumination  |
| FLUO_I(3)  |$M_f^b$    | Forward PS-I fluoresence matrix for abaxial illumination   |
| FLUO_I(4)  |$M_b^b$    | Backward PS-I fluoresence matrix for abaxial illumination  |
| FLUO_II(1) |$M_f^t$    | Forward PS-II fluoresence matrix for adaxial illumination  |
| FLUO_II(2) |$M_b^t$    | Backward PS-II fluoresence matrix for adaxial illumination |
| FLUO_II(3) |$M_f^b$    | Forward PS-II fluoresence matrix for abaxial illumination  |
| FLUO_II(4) |$M_b^b$    | Backward PS-II fluoresence matrix for abaxial illumination |

### 4. Citation

* Shi H. (2024). Exploring vegetation chlorophyll fluorescence with leaf dorsiventrality. (under review)
