# Móveis Pro — AR

**Móveis Pro — AR** é uma aplicação web desenvolvida para **visualização de móveis em Realidade Aumentada (AR)** diretamente no navegador, permitindo que usuários visualizem produtos em escala real no próprio ambiente físico, **sem necessidade de instalação de aplicativos**.

O projeto foi concebido com foco em **experiência do usuário**, **performance** e **compatibilidade multiplataforma**, sendo totalmente funcional em **iOS e Android** via tecnologias de **WebAR**.

---

## 🔗 Demo
👉 https://admirable-pithivier-8cf0de.netlify.app/

---

## 🎯 Objetivo do Projeto
Demonstrar a aplicação prática de **Realidade Aumentada no e-commerce e varejo digital**, possibilitando:
- Redução de incertezas na compra de móveis
- Melhor experiência de visualização para o cliente final
- Aumento de engajamento e conversão

---

## 🖼️ Visão Geral da Aplicação

### Interface Web
<img width="1220" alt="Visão geral da aplicação" src="https://github.com/user-attachments/assets/fb70fc00-0cb5-4e61-8df5-183c56e4cb63" />
<img width="1323" alt="Catálogo de móveis" src="https://github.com/user-attachments/assets/c083bf44-e071-40a1-80c6-e765ee8e313c" />
<img width="1200" alt="Detalhes do produto" src="https://github.com/user-attachments/assets/cf36cc66-5997-42c5-8449-df318dd48148" />
<img width="1068" alt="Visualização em ambiente" src="https://github.com/user-attachments/assets/75fb2ed5-88af-4ca7-9cdb-07031cacbc61" />
<img width="1062" alt="Interação com modelo 3D" src="https://github.com/user-attachments/assets/c2f5dc06-b9be-4bc4-8b62-f6474b58159d" />

### 📱 Experiência Mobile (WebAR)
<img width="360" alt="AR em dispositivo móvel" src="https://github.com/user-attachments/assets/2d2335cc-3410-43d7-886a-2cff95edb0f2" />
<img width="356" alt="Visualização do móvel em AR" src="https://github.com/user-attachments/assets/f83b9afb-f04d-4640-9a9e-9cb743642e41" />

---

## 🧠 Arquitetura & Decisões Técnicas
- Aplicação **WebAR**, eliminando dependência de apps nativos
- Renderização 3D otimizada para dispositivos móveis
- Uso de padrões web modernos para compatibilidade e desempenho
- Separação clara entre camada de interface e visualização 3D

### 📱 Compatibilidade
- **iOS:** Safari (AR Quick Look)
- **Android:** Chrome (WebXR)
- **Desktop:** Visualização 3D interativa

---

## 🪑 Funcionalidades Principais
- Visualização de móveis em escala real
- Posicionamento do objeto no ambiente físico
- Interação com modelos 3D
- Experiência responsiva e intuitiva
- Suporte multiplataforma (iOS, Android e Desktop)

---

## 🛠️ Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript
- WebAR
- `<model-viewer>`
- Three.js
- Netlify (CI/CD)

---

## 📦 Execução Local
```bash
npm install
npm run dev
