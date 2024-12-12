
<p align="center">
  <img src="https://github.com/user-attachments/assets/a63739e9-8475-4fb9-baaa-c39f0ef7cfc9" alt="INACTIVE BLOG - MOVED"/>
</p>


# 📘 Guia de Comandos Git

> Um repositório dedicado a explicar comandos essenciais do Git, organizado de forma prática e direta.

---

## 🌟 Comando: `git pull`

### 📖 O que faz:
> O comando `git pull` é usado para baixar as alterações do repositório remoto e mesclá-las automaticamente ao branch local ativo.  

### 📋 Sintaxe:
```bash
git pull <remote> <branch>
```

### 🛠️ Exemplo de uso:
```bash
git pull origin main
```

> Este comando baixa as alterações do branch `main` no repositório remoto `origin` e aplica ao branch local atual.

---

## 🌟 Comando: `git push`

### 📖 O que faz:
> O comando `git push` envia as alterações feitas localmente para o repositório remoto. Ele é usado para compartilhar commits com outros colaboradores.  

### 📋 Sintaxe:
```bash
git push <remote> <branch>
```

### 🛠️ Exemplo de uso:
```bash
git push origin main
```

> Este comando envia as alterações do branch local `main` para o branch remoto correspondente no repositório `origin`.

---

## 🌟 Comando: `git fetch`

### 📖 O que faz:
> O comando `git fetch` baixa as alterações do repositório remoto, mas **não as aplica automaticamente** ao branch local. Isso permite revisar as mudanças antes de integrá-las.  

### 📋 Sintaxe:
```bash
git fetch <remote>
```

### 🛠️ Exemplo de uso:
```bash
git fetch origin
```

> Este comando baixa as mudanças do repositório remoto `origin`, mas não altera o branch local automaticamente. Você pode integrar as alterações manualmente com um `git merge` ou outro comando.

---

## 🔎 Diferença entre `git pull` e `git fetch`

| Comando       | O que faz                                                                 |
|---------------|---------------------------------------------------------------------------|
| **`git pull`** | Baixa as mudanças e já aplica ao branch local.                           |
| **`git fetch`**| Apenas baixa as mudanças, sem aplicá-las automaticamente.                |

---

## 🎥 **Aula sobre Git e GitHub**

Para um aprofundamento mais completo sobre Git, incluindo exemplos práticos e explicações detalhadas, assista à aula no YouTube:

[**Git e GitHub - Aula Completa**](https://www.youtube.com/watch?v=kB5e-gTAl_s&t=1104s)

**Sobre a aula:**
> Neste vídeo, você aprenderá desde os conceitos básicos de Git e GitHub, até técnicas mais avançadas. A aula abrange:
> - Como usar comandos como `git pull`, `git push`, `git fetch` e outros.
> - Como configurar e usar o Git no seu computador.
> - Boas práticas de colaboração usando GitHub.

---

## 💡 Contribua!

Sinta-se à vontade para enviar sugestões ou novos exemplos de comandos Git. 🚀
