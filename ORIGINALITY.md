# Neurobiological Time Perception Hypothesis

## Mathematical Foundations

### 1. General Differential Form
$$
d\tau = \frac{K}{V_{\text{eff}}} \cdot \frac{dI}{I}
$$

*Notes*: 
- $V_{\text{eff}}$ = conscious information-processing volume (e.g., cortex in mammals, whole brain in insects)
- $K$ ≈ 1 (default), but may account for unknown metabolic/neurochemical parameters

### 2. Physical Solution (Definite Integral)
$$
\tau = \int_{I_0}^{I} \frac{K}{V_{\text{eff}}} \cdot \frac{dI}{I} = \frac{K}{V_{\text{eff}}} \ln\left(\frac{I}{I_0}\right) \quad \text{for } I \geq I_0
$$

### 3. Normalized Final Form (Recommended)
$$
\tau = \frac{K}{V_{\text{eff}}} \ln\left(1 + \frac{I}{I_0}\right) \quad \text{(ensures } \tau=0 \text{ at } I=0\text{)}
$$

## Biological Interpretation

### Key Parameters
| Parameter | Mathematical Role | Neurobiological Interpretation | Example Values |
|-----------|-------------------|--------------------------------|----------------|
| $V_{\text{eff}}$ | Processing volume | Active conscious tissue volume | Human: ~30,000 mm³ (cortex) |
| $I$ | Total information | Integrated synaptic activity | Human: ~10¹⁵ bits/s |
| $I_0$ | Threshold | Minimal conscious activation | ~10¹² bits/s |
| $K$ | Scaling factor | Metabolic/unknown efficiency | 0.5-1.5 range |

### Species Comparison
| Organism | $V_{\text{eff}}$ [mm³] | $I/I_0$ | $K$ | $\tau$ (relative) |
|----------|-----------------------|---------|-----|-------------------|
| Mayfly | 0.1 | 10 | 1.5 | 34.5 |
| Sparrow | 100 | 80 | 0.8 | 0.035 |
| Octopus | 300 | 120 | 1.2 | 0.019 |
| Human | 30,000 | 100 | 1.0 | 0.00015 |
| Elephant | 200,000 | 150 | 0.7 | 0.0000015 |

## Biological Predictions

1. **Sleep States**
   When $V_{\text{eff}}$ decreases by 40% during NREM sleep:
   $$
   \tau_{\text{sleep}} \approx 1.67 \times \tau_{\text{awake}}
   $$
   - *Mechanism*: Reduced cortical integration volume increases $\tau$

2. **Metabolic Scaling**
   For species with higher $K$ (metabolic efficiency):
   $$
   \Delta\tau \approx \frac{\Delta K}{V_{\text{eff}}} \ln(2)
   $$
## Novel Aspects

### 2. $K$ as Future-proof Parameter
The scaling factor $K$ can be decomposed as:

$$
K = 1 + \underbrace{\alpha_{\text{met}}}_{\text{metabolic efficiency}} + \underbrace{\beta_{\text{neuro}}}_{\text{neurotransmitter effects}} + \underbrace{\gamma_{\text{thermo}}}_{\text{temperature}} + \cdots
$$

Where:
- $\alpha_{\text{met}}$: Metabolic correction term (range: -0.3 to +0.5)  
  *Example*: +0.2 for endotherms with high mitochondrial density
- $\beta_{\text{neuro}}$: Neurochemical modulation (range: -0.1 to +0.3)  
  *Example*: +0.15 for serotonin-dominated systems
- $\gamma_{\text{thermo}}$: Q₁₀ temperature coefficient (~0.1 per 10°C)  

**Key Properties**:
1. Baseline $K=1$ for standard cortical tissue
2. Additive terms account for:
   - Known biological variability (measured)
   - Placeholders for future discoveries (theoretical)

## Comparative Advantages

| Feature | Traditional Models | This Hypothesis |
|---------|--------------------|-----------------|
| Volume Scaling | Linear/Negligible | **Logarithmic $V_{\text{eff}}$ dependence** |
| Threshold | Arbitrary | **$I_0$ as phase transition** |
| Cross-species | Challenging | **Unified $K/V_{\text{eff}}$ framework** |

## References
[1] Fechner's Law (1860) - Modified neural implementation  
[2] Integrated Information Theory (Tononi 2008) - Extended with volumetric constraints  
[3] Metabolic Theories of Time Perception - Incorporated via $K$ factor
