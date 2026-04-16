# .gitstore

Este repositório utiliza o **GitStore Marketplace** para divulgação e distribuição do projeto.

## O que é a pasta `.gitstore`?

A pasta `.gitstore` é criada automaticamente pelo GitStore quando você publica seu projeto no marketplace.

```
.gitstore/
  gitstore_readme.md ← este arquivo
  assets/            ← imagens do projeto (nome = SHA-256 do conteúdo)
    abc123def.jpg
    ...
```

## Por que isso é necessário?

- Permite que o GitStore identifique e indexe seu projeto no marketplace
- Mantém as imagens versionadas junto ao código
- O nome de cada imagem é o hash SHA-256 do seu conteúdo — garante integridade

## Não remova esta pasta

Remover a pasta `.gitstore` pode causar a remoção do projeto do marketplace.

---

*Gerado automaticamente pelo GitStore Marketplace*
