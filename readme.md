# 🚴 CicloRota Inteligente

Projeto criado para a Imersão IA 2025 (Alura + Google) com o objetivo de ajudar ciclistas a planejarem rotas seguras com o apoio da inteligência artificial generativa.

## 🎯 Objetivo

Este agente interativo coleta informações simples do ciclista (origem, destino, horário, nível e tempo diário de pedalada) e gera um resumo inteligente com:

- Estimativa de distância e tempo total de pedalada
- Tipo de terreno e infraestrutura provável (subidas, ciclovias)
- Dicas de segurança para o horário e perfil do ciclista
- Sugestões de preparo físico e ritmo diário

## 🛠️ Tecnologias Utilizadas

- Python
- Google Colab
- Gemini 2.0 Flash (`models/gemini-2.0-flash`)
- Biblioteca `google-generativeai`

## ▶️ Como Usar

1. Acesse o notebook no Google Colab
2. Insira sua chave da API Gemini (pode usar `userdata` do Colab)
3. Preencha as informações solicitadas:
   - Ponto de partida
   - Destino
   - Horário de saída
   - Nível como ciclista
   - Quantas horas por dia pretende pedalar
4. O agente da IA retorna um resumo com planejamento e orientações

## 📌 Exemplo de saída gerada

🚴 RESUMO DO TRAJETO

Distância estimada: 87 km
Tempo total estimado: 3 dias de pedalada

Terreno: predominantemente plano com trechos de subida na chegada. 60% de ciclovia ou acostamento.

Dicas: evite horário de pico na saída de Campinas. Use sinalizadores no trecho da rodovia SP-101.

Sugestão: mantenha ritmo leve nos dois primeiros dias. Faça pausas a cada 1h para hidratação.

## 📎 Licença

Uso livre para fins educacionais.


