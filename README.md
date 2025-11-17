# Atelier Budget

Organize seus projetos e calcule o preço certo em minutos, com receita e orçamento para compartilhar com seus clientes.

---

## 🚀 Como rodar o projeto

### 1. Instalar dependências
Na raiz do projeto, execute:
```bash
npm install
```
ou
```bash
yarn
```

---

## ▶️ Executar o app
Para iniciar o projeto em modo desenvolvimento:
```bash
npm start
```
ou
```bash
yarn start
```
ou
```bash
npx expo start -c
```
(O parâmetro `-c` limpa o cache do bundler.)

Isso abrirá o Expo, permitindo rodar no celular via QR Code ou em um emulador.

### Rodar no Android
```bash
npm run android
```
ou
```bash
yarn android
```

### Rodar no iOS (somente macOS)
```bash
npm run ios
```
ou
```bash
yarn ios
```

---

## 📦 Pacotes usados
Abaixo estão todos os pacotes encontrados no projeto, explicados e com instruções de instalação (caso precise adicionar manualmente).

## 🔹 Core
- **react** — Biblioteca principal de interface.
  ```bash
  npm install react
  ```

- **react-native** — Framework móvel.
  ```bash
  npm install react-native
  ```

- **expo** — Toolchain para desenvolvimento rápido.
  ```bash
  npm install expo
  ```

- **typescript** — Tipagem opcional.
  ```bash
  npm install -D typescript
  ```

- **@types/react** — Tipagens para React.
  ```bash
  npm install -D @types/react
  ```

  ---

## 🔹 Navegação
- **@react-navigation/native** — Core da navegação.
  ```bash
  npm install @react-navigation/native
  ```

- **@react-navigation/native-stack** — Navegação em pilha.
  ```bash
  npm install @react-navigation/native-stack
  ```

- **react-native-screens** — Performance na navegação.
  ```bash
  npm install react-native-screens
  ```

- **react-native-safe-area-context** — Áreas seguras.
  ```bash
  npm install react-native-safe-area-context
  ```

---

## 🔹 UI, Ícones e Status Bar
- **@expo/vector-icons** — Ícones integrados ao Expo.
  ```bash
  npm install @expo/vector-icons
  ```

- **expo-status-bar** — Controle da status bar.
  ```bash
  npm install expo-status-bar
  ```

---

## 🔹 Formulários e validação
- **react-hook-form** — Gestão de formulários.
  ```bash
  npm install react-hook-form
  ```

- **@hookform/resolvers** — Integração com validação.
  ```bash
  npm install @hookform/resolvers
  ```

- **zod** — Validação moderna.
  ```bash
  npm install zod
  ```

- **yup** — Validação baseada em schemas.
  ```bash
  npm install yup
  ```

---

## 🔹 Backend e dados
- **@supabase/supabase-js** — Conexão com Supabase.
  ```bash
  npm install @supabase/supabase-js
  ```

- **base64-arraybuffer** — Conversões base64 ↔ ArrayBuffer.
  ```bash
  npm install base64-arraybuffer
  ```

- **uuid** — Geração de UUIDs.
  ```bash
  npm install uuid
  ```

- **react-native-get-random-values** — Necessário para UUID.
  ```bash
  npm install react-native-get-random-values
  ```

- **@react-native-async-storage/async-storage** — Armazenamento local.
  ```bash
  npm install @react-native-async-storage/async-storage
  ```

---

## 🔹 Inputs, seleção e componentes nativos
- **@react-native-picker/picker** — Dropdown nativo.
  ```bash
  npm install @react-native-picker/picker
  ```

---

## 🔹 APIs de dispositivo e arquivos (Expo)
- **expo-device** — Info do dispositivo.
  ```bash
  npm install expo-device
  ```

- **expo-document-picker** — Selecionar arquivos.
  ```bash
  npm install expo-document-picker
  ```

- **expo-file-system** — Manipular arquivos.
  ```bash
  npm install expo-file-system
  ```

- **expo-linking** — Deep linking.
  ```bash
  npm install expo-linking
  ```

- **expo-notifications** — Notificações.
  ```bash
  npm install expo-notifications
  ```

---



### Navegação
- **@react-navigation/native**
- **@react-navigation/native-stack**

### Backend
- **@supabase/supabase-js** — conexão com banco e autenticação.

### Armazenamento local
- **@react-native-async-storage/async-storage** — salvar dados simples no dispositivo.

### Formulários / utilidades (se usados)
- **react-hook-form** — controle de formulários.
- **yup** — validação.

## 📁 Estrutura mínima do projeto
```
src/
  auth/
  common/
  components/
  img/
  lib/
  screens/
  services/
  theme/
  utils/
  supabase/
```

