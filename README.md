# Prompt Studio 🤖

Gerador de prompts estruturados em JSON para uso com Cursor e outras ferramentas de IA.

## O que faz

- Monta prompts com **Persona**, **Objetivo**, **Temperatura**, **Contexto**, **Steps** e **Restrições**
- Gera JSON no formato v2.0 compatível com regras do Cursor
- Copia direto para o clipboard — basta colar no chat

## Como usar

1. Abra o `index.html` no navegador
2. Preencha os campos
3. Clique em **GERAR E COPIAR PARA O CURSOR**
4. Cole o JSON no chat do Cursor

## Formato do JSON

```json
{
  "version": "2.0",
  "config": {
    "role": "...",
    "goal": "...",
    "temperature": 0.7,
    "output_format": "JSON"
  },
  "prompt_details": {
    "context": "...",
    "execution_steps": ["..."],
    "constraints": ["..."]
  }
}
```

## Temperatura

- **0** = mais determinístico (código, fatos)
- **1** = mais criativo (brainstorm, ideias)

## Licença

MIT
