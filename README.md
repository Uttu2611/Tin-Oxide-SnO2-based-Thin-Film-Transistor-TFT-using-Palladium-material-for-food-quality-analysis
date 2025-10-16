# Tin-Oxide-SnO2-based-Thin-Film-Transistor-TFT-using-Palladium-material-for-food-quality-analysis

## Introduction
<div style="text-align: justify;">
Field Effect Transistors (FETs) play a crucial role in modern electronic devices, forming the foundation of integrated circuits. Simulation of Organic FETs (OFETs) facilitates the analysis and optimization of important parameters like on-current, threshold voltage, and on/off ratio, which are very important to improve the performance of thin-film transistors (TFTs). Technology Computer-Aided Design (TCAD) software allows simulations of semiconductor behavior with high accuracy, and therefore they provide a useful hint before physical realization.
</div>

<div style="text-align: justify;">
Materials such as Titanium Dioxide (TiO₂) and Amorphous Indium-Gallium-Zinc Oxide (a-IGZO) are extensively studied for TFT deployment, yet stability under different biasing conditions remains a problem. To extend beyond such limitations, Palladium-assisted MOSFET architectures have been reported for applications in sensing gases. Here, Silicon-based MOSFET using SiO₂ as the dielectric with Palladium above the channel is proposed for toxic gas detection related to food decay. The back-gate structure improves carrier modulation and sensitivity to response. TCAD simulations analyze the device's output and transfer characteristics, which testifies to its potential to be an efficient gas sensor for food safety monitoring.
</div>

## Device Structure
<p style="text-align: justify;">
<img width="638" height="391" alt="image" src="https://github.com/user-attachments/assets/9d28a9b7-0fb5-4c0d-9ecf-2c8edc923361" />
</p>
<p style="text-align: justify;">
Figure 1 shows the cross-sectional structure of the presented Thin Film Transistor (TFT) gas sensor, with the structural details tabulated in Table 1. The device is based on a back-gated Field Effect Transistor (FET) structure, wherein the gate is realized by a heavily doped p-type silicon substrate, and metal electrodes are used to demarcate the source and drain regions. The silicon nanowire channel offers a high surface-to-volume ratio, which improves the overall sensing sensitivity.
</p>
<p style="text-align: justify;">
A Palladium (Pd) layer is deposited on top of the silicon channel, serving as the gas-sensing material because of its high catalytic activity. Upon exposure to hydrogen-based or other poisonous gases, the Palladium layer adsorbs the gas molecules, resulting in a change in its work function. This change alters the drain current, facilitating gas detection through quantifiable electrical response.
</p>
<p style="text-align: justify;">
The output behavior of the device was examined for different gate work functions to investigate their effect on current variation and sensitivity. In the absence of the Palladium layer, the device exhibits merely baseline current changes and fails to detect gases. By including the Pd layer, the transistor can successfully detect and measure toxic gases and is well suited for food safety and environmental monitoring applications.
</p>

| Parameter | Values |
|---|---|
| Channel length | 7 μm|
|  Channel width | 120 μm |
|   Oxide thickness | 500 nm |
|  Doping density | 1.59 × 10^–23 m^–3 |
|   Silicon oxide |  3.9 nm |

## Result & Analysis
This section discusses the performance analysis of the proposed device structure. The output and transfer characteristics were examined to understand the current-driving behavior of the transistor. By varying the gate work function and integrating Palladium (Pd) as a sensing layer, the device’s response was compared with that of a conventional MOSFET without the sensing material. The results show a notable improvement in drain current and sensitivity, confirming the effectiveness of incorporating the Palladium layer. This enhancement highlights the potential of the proposed design for reliable gas detection and high-performance sensing applications.

### Experimental Validation
<img width="756" height="387" alt="image" src="https://github.com/user-attachments/assets/757c211e-5c31-41e9-ba5f-206cb681295d" />

<p style="text-align: justify;">
Figure 2 illustrates the output characteristics of a ZnO₂ TFT structure designed by Chakraborty & Roy Chaudhari [10], which has been validated using the proposed simulation model. The drain-to-source voltage was swept from 0 V to 3 V to analyze device behavior. The TCAD simulation tool was employed to reproduce the experimental characteristics of the conventional ZnO₂ TFT, ensuring accurate model validation.
</p>
<p>
To simulate the device physics, several physical models were incorporated, including impact ionization and Shockley–Read–Hall (SRH) generation-recombination mechanisms. These models enable precise evaluation of carrier generation and recombination processes, forming the basis for analyzing the transistor’s output characteristics and confirming the reliability of the proposed simulation framework.
</p>

### Without Palladium Materia
<img width="842" height="400" alt="image" src="https://github.com/user-attachments/assets/af4c4da6-f537-46b7-bf4f-f5f306a31b8e" />
<img width="853" height="443" alt="image" src="https://github.com/user-attachments/assets/de58b2fe-9986-4add-b503-a24a0a7168b7" />

<p>
Figure 3 shows the output characteristics of the proposed device, demonstrating the effect of varying gate work functions on the drain current. As the drain voltage was swept from 0 to 3 V, the maximum saturation current of 9.01 μA was achieved at a gate work function of 4.8 eV, indicating strong sensitivity to work function variations caused by gas interaction.</p>
<p>
Figure 4 presents the transfer characteristics, where the gate bias was varied from 0 to 3 V. A peak current of 9.1 μA was obtained at a gate work function of 4 eV, confirming the device’s responsiveness to gate bias and Palladium’s effective role in enhancing gas detection sensitivity.</p>

<img width="821" height="438" alt="image" src="https://github.com/user-attachments/assets/eabee31e-6207-49d9-9b74-16434d0b9c03" />

<p> Figure 5 depicts the ID–VG characteristics and trans-conductance curves for the proposed structure. The analysis is performed with a constant drain volt age of 3 V. A peak trans-conductance value of nearly
 5.5 S has been observed in relation to the gate-to source voltage. The proposed TFT device achieves a maximum gm of 5.5 S and a maximum drain current of 9.1 A. The trans-conductance starts to decrease at 2.5 to 3 V gate to-source voltage, demonstrating TiO2’s control over the charge distribution in the channel.</p>
  
<img width="823" height="443" alt="image" src="https://github.com/user-attachments/assets/97259515-7b5f-4ea8-9b5c-5e00002a1e8f" />

<p> Figure 6 depicts the comparison of drain current at different work functions. Various peak drain currents at different metal work functions are compared in Fig. 6. A lower work function value for the gate material is correlated with a higher yielding of current drive. It is possible to determine the ideal value for detecting the presence of the nickel layer by varying the gate’s work function into many values. When compared to ZnO2 based TFT structures, TiO2 devices often have higher threshold voltage and limited gate control due to its confined subthreshold swing. ZnO2 based TFTs are equally effective when used in displays, transparent electronics, flexible sensors, meanwhile TiO2-based TFTs can be considered a best option for being used in dielectric layers, sensor applications, memory structures etc. A comparison of the properties of ZnO2 and TiO2 based TFTs have been given in Table 2.</p>

| Parameter | ZnO2-based TFT |  Proposed TiO2-based TFT |
|---|---|---|
| Threshold voltage (Vth) | 0.5 V | 2.25 V |
| On-off current ratio | 10^(7) | 10^(5) |
| Defect density | Moderate but still sensitive to oxygen vacancies | Higher; having oxygen vacancies |
| Maximum drain current | 1.35 × 10(–7) A | 1.5 × 10(-7) A |
|  Subthreshold swing | 380 | 1.1 |

### After Placing Palladium Material

<img width="838" height="456" alt="image" src="https://github.com/user-attachments/assets/fbfc6023-2583-443a-8b0e-73bdc1465304" />

<img width="697" height="452" alt="image" src="https://github.com/user-attachments/assets/67a5f6ef-16d9-49dd-9114-759edd4ec0ac" />


<p>Palladium (Pd) is an excellent sensing material due to its strong affinity for hydrogen, high sensitivity, and rapid response time. In the proposed design, the Pd layer is simulated over the TFT surface to replicate gas detection behavior. As shown in Figure 7, the drain current decreases after adding the Pd layer, indicating its interaction with target gases.</p>

<p>The transconductance (gₘ) characteristics in Figure 8 also show a noticeable reduction (around 4 S), confirming that Pd influences the device’s electrical response. Figure 9 compares the output characteristics for varying TiO₂ dielectric thicknesses, where a 300 nm layer yields a peak saturation current of 3.74 μA. Additionally, an increase in AlGaN thickness causes a negative threshold voltage shift (Vₜ) due to dielectric effects, validating the sensitivity and tunability of the proposed structure.</p>

<img width="677" height="469" alt="image" src="https://github.com/user-attachments/assets/b7a3f2a3-97c5-4c07-bdf5-e09931773643" />











