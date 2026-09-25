# Painel Integração 360

**Grupo Maroni / Transmaroni** — Integração de Condutor & Jornada
(Trimble × Ponto × Identificação facial × Alertas), por **motorista + dia**.

Cruza folha de ponto, movimentação do veículo, identificação da câmera e alertas de telemetria
para apontar divergências (veículo sem ponto, condutor divergente, condução fora da jornada,
descanso entre jornadas abaixo da CLT), medir **aderência de jornada** e gerar fichas por motorista.

## Como funciona

- **Página única** (`index.html`) — HTML + CSS + JavaScript, **sem backend**. Abre no navegador.
- Publicada via **GitHub Pages**: https://maronitechdevelopers.github.io/integracao-360/
- Não há versão em Python — toda a lógica roda no navegador, em JS.

## Publicar

Edite a versão de trabalho (`../PROJETOS/Dedo Duro/Painel-Ponto-x-Movimentacao-x-Trimble.html`) e rode:

```
publicar.bat
```

(ele copia para `index.html`, faz commit e `git push origin main`).

## Documentação completa

👉 **[DOCUMENTACAO.md](DOCUMENTACAO.md)** — arquitetura, fontes de dados, modelo de dados, regras de
negócio e cálculos, configurações, telas, integração Microsoft 365, segurança, glossário, inventário
de funções e guia de manutenção.

## Arquivos

| Arquivo | Papel |
|---|---|
| `index.html` | O painel publicado (cópia da versão de trabalho) |
| `DOCUMENTACAO.md` | Documentação técnica completa |
| `publicar.bat` | Script de publicação (copiar + commit + push) |
| `dados.enc` | Snapshot criptografado dos dados (opcional; inútil sem a chave do link) |
