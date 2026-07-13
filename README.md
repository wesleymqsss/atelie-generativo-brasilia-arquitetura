# 🏛️ Fine-Tuning LoRA para Geração de Imagens da Arquitetura de Brasília

Projeto com o objetivo de especializar um modelo de difusão utilizando a técnica de **Fine-Tuning com LoRA (Low-Rank Adaptation)** para gerar imagens inspiradas na arquitetura modernista de Brasília.

---

## 📖 Sobre o Projeto

Brasília é reconhecida mundialmente por sua arquitetura modernista, projetada por Oscar Niemeyer e pelo planejamento urbano de Lúcio Costa. Este projeto busca explorar modelos de Inteligência Artificial Generativa para reproduzir características visuais desse patrimônio arquitetônico.

Por meio da técnica de **LoRA**, foi possível adaptar um modelo de difusão pré-treinado para aprender padrões específicos da arquitetura brasiliense, mantendo baixo custo computacional e alta eficiência no treinamento.

---

## 🎯 Objetivos

- Criar um dataset especializado contendo imagens da arquitetura de Brasília;
- Realizar o pré-processamento e organização do conjunto de dados;
- Executar o fine-tuning utilizando LoRA;
- Avaliar a capacidade do modelo em reproduzir características da arquitetura modernista;
- Demonstrar o potencial da IA Generativa aplicada ao patrimônio arquitetônico.

---

## 🖼️ Dataset

O dataset foi composto por imagens de edificações e monumentos representativos da arquitetura de Brasília, incluindo diferentes perspectivas, condições de iluminação e enquadramentos.

As imagens passaram por etapas de:

- seleção;
- organização;
- padronização;
- criação de captions;
- preparação para treinamento.

O objetivo foi fornecer diversidade suficiente para que o modelo aprendesse o estilo arquitetônico característico da cidade.

---

## ⚙️ Metodologia

A metodologia utilizada foi baseada em **Fine-Tuning com LoRA (Low-Rank Adaptation)**.

### Etapas do projeto

```text
Coleta das imagens
        ↓
Construção do Dataset
        ↓
Pré-processamento
        ↓
Criação das Captions
        ↓
Fine-Tuning com LoRA
        ↓
Modelo Especializado
        ↓
Geração de Imagens
        ↓
Avaliação dos Resultados
```

A técnica LoRA permite adaptar modelos de difusão adicionando pequenas matrizes treináveis aos pesos do modelo original, reduzindo significativamente o custo computacional quando comparado ao treinamento completo (Full Fine-Tuning).

---

## 🚀 Tecnologias Utilizadas

- Python
- PyTorch
- Diffusers
- LoRA (Low-Rank Adaptation)
- Stable Diffusion
- Hugging Face
- CUDA (quando disponível)

---

---

## 🧠 Fine-Tuning

O treinamento foi realizado utilizando LoRA, permitindo especializar o modelo para reconhecer padrões específicos da arquitetura de Brasília sem modificar integralmente os pesos do modelo base.

Entre as principais vantagens da abordagem estão:

- menor consumo de memória;
- treinamento mais rápido;
- menor quantidade de parâmetros treináveis;
- facilidade para reutilização do modelo.

---

## 🖼️ Resultados

Após o treinamento, o modelo demonstrou capacidade de gerar imagens que preservam características marcantes da arquitetura modernista de Brasília, como:

- curvas características;
- concreto branco;
- grandes vãos livres;
- simetria;
- monumentalidade;
- integração entre arquitetura e espaço urbano.

Os resultados foram avaliados qualitativamente por meio da comparação entre as imagens geradas e as referências utilizadas no treinamento.

---

## ⚠️ Limitações

- O desempenho depende diretamente da qualidade e diversidade do dataset.
- Prompts muito genéricos podem produzir resultados menos fiéis ao estilo arquitetônico.
- O modelo pode reproduzir limitações presentes nos dados utilizados durante o treinamento.

---

## 🔮 Trabalhos Futuros

- Expandir o dataset com novos edifícios de Brasília;
- Utilizar imagens em diferentes horários e condições climáticas;
- Testar modelos de difusão mais recentes;
- Explorar ControlNet e outras técnicas de condicionamento;
- Avaliar quantitativamente a qualidade das imagens geradas.

---

## 👥 Equipe

Projeto desenvolvido para a disciplina de **Ateliê Generativo**.

---

## 📄 Licença

Este projeto possui finalidade exclusivamente acadêmica.

As imagens utilizadas no treinamento devem respeitar seus respectivos direitos autorais e licenças de uso.