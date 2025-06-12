# 🧑‍💻 Configurando o Docker dentro do Kali Linux via WSL

Este repositório contém as etapas que segui para utilizar o Docker — já instalado no meu sistema operacional Windows — dentro do sistema operacional Kali Linux, que configurei via **WSL (Windows Subsystem for Linux)**.

O objetivo deste repositório é documentar o processo para futuras referências e também ajudar outras pessoas a fazerem o mesmo.

---

## ✅ Requisitos

- Windows 11
- Subsistema WSL habilitado
- Acesso à Microsoft Store ou terminal para instalar distribuições Linux
- Docker Desktop instalado no Windows

---

## 🚀 Etapas para habilitar o Docker no WSL

### 1️⃣ Abrir o Docker Desktop no Windows

### 2️⃣ Acessar as configurações (⚙️)

- Vá em **Settings → Resources → WSL Integration**

### 3️⃣ Ativar a integração com o Kali Linux

- Marque a opção `kali-linux` (ela vem desabilitada por padrão)

### 4️⃣ Testar no terminal do Kali

Abra o terminal do Kali Linux e execute:

```bash
docker --version
