# Prompt Studio

Gerador de prompts estruturados em JSON para Cursor e outras ferramentas de IA.

**No ar:** [davibragaba.github.io/Prompt-Json](https://davibragaba.github.io/Prompt-Json/)

## O que faz

- Monta prompts com **Persona**, **Objetivo**, **Temperatura**, **Contexto**, **Steps** e **Restrições**
- Gera JSON no formato v2.0, pensado para colar no chat do Cursor
- Copia direto para o clipboard

## Como usar

1. Abra o site acima (ou o `index.html` no navegador)
2. Preencha os campos
3. Clique em **GERAR E COPIAR PARA O CURSOR**
4. Cole o JSON no chat

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

- **0** — mais determinístico (código, fatos)
- **1** — mais criativo (brainstorm, ideias)

## Licença

MIT
