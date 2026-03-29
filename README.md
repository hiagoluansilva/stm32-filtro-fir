# STM32 Filtro FIR — Filtro de Resposta ao Impulso Finita

🇧🇷 **Português** | 🇺🇸 [English](#english)

---

## Português

Implementação de filtro FIR (Finite Impulse Response) em STM32F4xx, projetado para filtragem de sinais em tempo real via ADC/DAC.

### O que faz
- Implementa filtro **FIR** para seleção de frequências no sinal de entrada
- Coeficientes definidos em tempo de compilação
- Pipeline: ADC → FIR → DAC
- Usa **CMSIS-DSP** ou implementação manual dos coeficientes

### Conceito FIR
```
y[n] = Σ h[k] · x[n-k]   (k = 0..N-1)
```

### Microcontrolador
STM32F4xx — Atollic TrueSTUDIO

---

## English

FIR (Finite Impulse Response) filter implementation on STM32F4xx, designed for real-time signal filtering via ADC/DAC.

### What it does
- Implements **FIR** filter for frequency selection on the input signal
- Coefficients defined at compile time
- Pipeline: ADC → FIR → DAC
- Uses **CMSIS-DSP** or manual coefficient implementation

### FIR concept
```
y[n] = Σ h[k] · x[n-k]   (k = 0..N-1)
```

### MCU
STM32F4xx — Atollic TrueSTUDIO
