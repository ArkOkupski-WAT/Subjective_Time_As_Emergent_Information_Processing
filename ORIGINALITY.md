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

## Metabolic Scaling
In species with higher metabolic efficiency (represented by parameter K), changes in subjective time perception scale logarithmically with changes in K relative to effective processing volume.

## Novel Aspects

### 2. K as Future-proof Parameter
The scaling factor K incorporates multiple biological components:
- Metabolic efficiency (α_met)
- Neurotransmitter effects (β_neuro)
- Temperature influences (γ_thermo)
- And other potential factors

The relationship shows that K represents more than just simple processing speed, but rather a composite of various biological efficiencies.

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
