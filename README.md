# stm32-filtro-fir

Filtro FIR passa-baixa implementado com a biblioteca CMSIS-DSP no STM32F446RE.

## Descrição

Implementação de filtro FIR (Finite Impulse Response) passa-baixa utilizando as funções otimizadas da ARM CMSIS-DSP Library, aproveitando as instruções SIMD do núcleo Cortex-M4 com FPU.

## Hardware

- Microcontrolador: STM32F446RE

## Tecnologias

- **CMSIS-DSP** — `arm_fir_f32`
- Coeficientes calculados conforme teoria de projeto de filtros digitais (janela, equirripple, etc.)

## Conceitos abordados

- Teorema de Nyquist e taxa de amostragem
- Projeto de filtros FIR por janelamento
- DSP em tempo real com Cortex-M4

## Estrutura do projeto

```
filtroCMSIS_FIRLP/
├── Src/
├── Inc/
├── Drivers/    # CMSIS-DSP incluído
└── STM32F446RE_FLASH.ld
```

## Referências

- ARM CMSIS-DSP Library Documentation
- Sedra — Microeletrônica (5ª ed.)

## Escola

Centro Tecnológico Liberato — Novo Hamburgo/RS
