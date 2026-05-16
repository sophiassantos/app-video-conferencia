# 🐾 VetConnect
**Cuide do seu pet. De onde estiver.**

VetConnect é um aplicativo Android que conecta tutores de animais a 
veterinários para consultas online em tempo real — com agendamento, 
pagamento integrado e videoconferência, tudo em um único app.

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Jitsi](https://img.shields.io/badge/Jitsi_Meet-97979A?style=flat&logo=jitsi&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

---

## ✨ Proposta de Valor — Por que o VetConnect é único?

A maioria das soluções de telemedicina veterinária exige múltiplos 
aplicativos: um para agendamento, outro para pagamento e outro para 
videochamada. O VetConnect elimina essa fricção:

| Recurso | VetConnect | Soluções comuns |
|---|---|---|
| Lista de veterinários disponíveis | ✅ | ✅ |
| Agendamento com dados do pet | ✅ | ⚠️ parcial |
| Pagamento integrado no app | ✅ | ❌ |
| Videoconferência embutida (Jitsi) | ✅ | ❌ |
| Sala privada gerada automaticamente | ✅ | ❌ |
| Chat durante a consulta | ✅ | ❌ |
| Sem redirecionamento externo | ✅ | ❌ |

Em resumo: escolha o veterinário, informe os dados do seu pet, pague 
e entre na consulta — tudo sem sair do app.

---

## 📸 Capturas de Tela

> Adicione aqui os screenshots ou GIFs da aplicação rodando.

| [ Splash Screen ] | [ Lista de Veterinários ] |
|---|---|
| [ Agendamento de Consulta ] | [ Tela de Pagamento ] |
| [ Videoconferência Jitsi ] | [ Chat durante a consulta ] |

---

## 🚀 Instruções de Uso

### Pré-requisitos

- Android Studio Hedgehog ou superior
- Android SDK 24+
- JDK 17

### Instalação

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/vetconnect.git
cd vetconnect

# 2. Abra no Android Studio
# File → Open → selecione a pasta do projeto

# 3. Sincronize as dependências Gradle
# Android Studio fará isso automaticamente

# 4. Execute o projeto
# Clique em Run ▶ ou use Shift + F10
```

### Como usar

**Agendando uma consulta:**
1. Na tela inicial, veja a lista de veterinários disponíveis
2. Toque no veterinário desejado
3. Informe o nome do pet e o motivo da consulta
4. Confirme o agendamento

**Realizando o pagamento:**
1. Revise os dados da consulta
2. Toque em **Pagar** para confirmar
3. Você será direcionado para a sala de espera

**Na consulta:**
1. A videoconferência é iniciada automaticamente via Jitsi Meet
2. Uma sala privada exclusiva é gerada para cada consulta
3. Use o chat integrado para enviar mensagens durante a chamada

---

## 🛠️ Stack Tecnológica

| Camada | Tecnologia |
|---|---|
| Linguagem | Kotlin |
| UI | XML Layouts + ViewBinding |
| Arquitetura | MVVM (ViewModel + LiveData) |
| Videoconferência | Jitsi Meet SDK 9.2.2 |
| Navegação | Activities + Intents |
| Build | Gradle + Android SDK 34 |

---

## 📁 Estrutura do Projeto
