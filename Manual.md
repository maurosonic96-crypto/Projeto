# ☁️ Manual do Projeto cloud-so-app

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=nodedotjs\&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge\&logo=express\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge\&logo=render\&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge\&logo=visualstudiocode\&logoColor=white)

</div>

<div align="center">

<img src="https://media.giphy.com/media/kH1DBkPNyZPOk0BxrM/giphy.gif" width="90">
<img src="https://media.giphy.com/media/coxQHKASG60HrHtvkt/giphy.gif" width="90">
<img src="https://media.giphy.com/media/XAxylRMCdpbEWUAvr8/giphy.gif" width="90">

</div>

---

## 📌 Visão Geral

O **cloud-so-app** é uma aplicação backend desenvolvida com **Node.js + Express** para exibir informações do sistema operacional e publicar o serviço em nuvem usando **Render**.

### 🎯 Objetivos acadêmicos

* Aplicar conceitos de Sistemas Operacionais
* Criar API REST simples
* Versionar projeto no GitHub
* Realizar deploy em cloud
* Comparar ambiente local x remoto

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Função                         |
| ---------- | ------------------------------ |
| Node.js    | Runtime JavaScript no servidor |
| Express.js | Framework backend              |
| GitHub     | Versionamento                  |
| Render     | Hospedagem cloud               |
| VS Code    | Desenvolvimento                |
| módulo os  | Informações do sistema         |

---

## 📥 Instalação do Ambiente

| Ferramenta | Verificação     |
| ---------- | --------------- |
| Node.js    | `node -v`       |
| npm        | `npm -v`        |
| Git        | `git --version` |

---

## 📁 Criação do Projeto

```bash
mkdir cloud-so-app
cd cloud-so-app
npm init -y
npm install express cors
```

### Estrutura esperada

| Arquivo/Pasta | Finalidade             |
| ------------- | ---------------------- |
| index.js      | Servidor principal     |
| package.json  | Dependências           |
| node_modules  | Bibliotecas instaladas |

---

## ▶️ Execução Local

```bash
node index.js
```

### Testes

| URL                                | Função           |
| ---------------------------------- | ---------------- |
| `http://localhost:3000`            | Página inicial   |
| `http://localhost:3000/api/system` | Dados do sistema |

---

## 🌐 GitHub

```bash
git init
git add .
git commit -m "Projeto cloud-so-app"
git push
```

### Resultado

✔ Código salvo
✔ Histórico de versões
✔ Integração com Render

---

## ☁️ Deploy no Render

| Campo         | Valor Correto   |
| ------------- | --------------- |
| Build Command | `npm install`   |
| Start Command | `node index.js` |

### Fluxo

GitHub → Render → Build → Start → URL pública

---

## ⚠️ Problema Encontrado

### Erro

```bash
index.js: command not found
```

### Motivo

O sistema tentou executar `index.js` como programa Linux.

### Correção

```bash
node index.js
```

---

## 💻 Conceitos de Sistemas Operacionais Aplicados

| Conceito      | Aplicação no Projeto  |
| ------------- | --------------------- |
| Processo      | Execução do Node.js   |
| CPU           | Atende requisições    |
| Memória RAM   | Uso do servidor       |
| Hostname      | Nome da máquina       |
| Uptime        | Tempo ligado          |
| Kernel        | Base do sistema       |
| Virtualização | Infraestrutura Render |

---

## 🔍 Comparação Local x Cloud

| Item     | Local               | Cloud            |
| -------- | ------------------- | ---------------- |
| Hostname | Seu PC              | Servidor virtual |
| SO       | Windows/Linux local | Linux remoto     |
| CPU      | Física              | Virtual          |
| Memória  | Própria             | Compartilhada    |
| Acesso   | Local               | Internet         |

---

## 📚 Conclusão

Este projeto demonstrou na prática:

✅ Backend moderno
✅ API REST
✅ Deploy real em nuvem
✅ Logs e troubleshooting
✅ Relação entre software e sistema operacional

---

## 🚀 Próximas Evoluções

* Frontend HTML/CSS
* Dashboard visual
* Banco de dados
* Docker
* Monitoramento em tempo real


---

## 👨‍💻 Projeto Acadêmico

**FATEC — Sistemas Operacionais + Cloud Computing + Backend**

---
