# Anotações - Azure Language Studio

## O que é o Language Studio?

Ferramenta que usa IA para análise de linguagem natural. Permite:
- *Análise de sentimentos*
- *Extração de frases-chave*
- *Reconhecimento de entidades*
- *Classificação de texto*
- *Detecção de idioma*

---

## Exemplo demonstrado em aula:

*Texto analisado:* "Passei férias maravilhosa na França"

*Resultado:*
- Idioma: Português
- Sentimento: Positivo (score: 0.88)
- Frase-chave: "férias maravilhosa"
- Entidade reconhecida: França (Localização)

---

## Aplicações práticas

- Análise de comentários de usuários (e-commerce, redes sociais, turismo)
- Extração de dados úteis para negócios
- Classificação de reclamações/sugestões
- Suporte automatizado em empresas

---

## Classificação por intenção

Usa machine learning para entender o propósito de um texto:
- "Quero cancelar meu pedido" → Intenção: Cancelamento
- "Qual o horário de funcionamento?" → Intenção: Informação

---

## Requisitos de uso

- Recurso do Azure criado com serviço de Text Analytics
- Necessário API Key e Endpoin
