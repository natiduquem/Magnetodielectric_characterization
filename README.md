# Magnetodielectric Materials Characterization using Artificial Neural Network
This repository contains the dataset and the notebook used to train an ANN to retrieve the permittivity and permeability of a magnetodielectric material. The training data were obtained from the analysis of the SRR sensor’s frequency response.

Autors: 
G. Álvarez-Botero*, N. Duque-Madrid*, H. Lobato-Morales**, G. Méndez-Jerónimo**, K. Hui3, N. Tarabay***, A. Pons-Abenza*, I. Arregui*, T. Lopetegi*, M. A. G. Laso*, C. Velez***

*Institute of Smart Cities (ISC), Department of Electrical, Electronic and Communications Engineering, Public University of Navarre (UPNA), Campus Arrosadia, 31006 Pamplona, España.

**Departamento de Electrónica y Telecomunicaciones, CICESE, Ensenada 22860, México.

***Mechanical and Aerospace Engineering Department, Magnetic Microsystems and Microrobotics Laboratory, University of California, Irvine, CA, 92697, USA.

### Dataset Description: 
The dataset has been generated through full-wave electromagnetic simulations in CST. The dataset contains 2554 samples with following features:

#### Permittivity Features:

* 'fr_ε': Resonance frecuency
* 'Γ_ε' : Minimum reflection coefficient
* 'Loss_ε': Losses
* 'Bw_ε': Bandwidth

#### Permeability Features:

'fr_μ': Resonance frecuency

'Γ_μ': Minimum reflection coefficient

'Loss_μ': Losses

'Bw_μ': Bandwidth
#### Target Variables:
'Permittivity_μr'
'Permeability_εr'
'tanδε'
'tanδμ'
