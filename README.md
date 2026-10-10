# 💜 D&M — David & Malu

<p align="center">
  <strong>Um pequeno universo, feito para duas pessoas.</strong>
</p>

<p align="center">
  Um projeto Android dedicado a transformar conversas, fotografias, lembranças e pequenos momentos em um espaço compartilhado por David e Malu.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Plataforma-Android-7C6AA6?style=for-the-badge&logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/Linguagem-Kotlin-7C6AA6?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/UI-Jetpack%20Compose-B8A9D9?style=for-the-badge" alt="Jetpack Compose">
  <img src="https://img.shields.io/badge/Status-Em%20desenvolvimento-E8A8C4?style=for-the-badge" alt="Em desenvolvimento">
</p>

---

## ✨ Sobre o projeto

**D&M — David & Malu** é um aplicativo Android desenvolvido com Kotlin e Jetpack Compose, idealizado como um ambiente digital privado para um casal.

A proposta é reunir em um só lugar recursos que fazem parte da vida a dois: conversas, fotos, arquivos, histórias e memórias compartilhadas. Mais do que um exercício de programação, o D&M é um projeto pessoal de desenvolvimento de software, criado para aprender, experimentar e construir algo com identidade própria.

A ideia é simples: em vez de ser mais uma rede social, o aplicativo deve funcionar como um pequeno espaço particular, pensado para duas pessoas.

> *Algumas histórias não precisam de uma plateia. Só de um lugar para existir.*

## 🎨 Identidade visual

O D&M adota uma estética intimista, elegante e contemporânea, inspirada em tons noturnos, lavanda e detalhes suaves.

| Cor                   | Código hexadecimal | Aplicação                        |
| --------------------- | ------------------ | -------------------------------- |
| Azul-marinho profundo | `#101426`          | Fundo principal                  |
| Azul-marinho suave    | `#1A1F38`          | Superfícies e balões de mensagem |
| Roxo                  | `#7C6AA6`          | Cor de destaque                  |
| Lavanda               | `#B8A9D9`          | Elementos visuais e mensagens    |
| Branco suave          | `#F8F7FA`          | Textos claros                    |
| Cinza suave           | `#B9B7C2`          | Informações secundárias          |
| Rosa delicado         | `#E8A8C4`          | Destaques e estados de gravação  |

A intenção visual é transmitir aconchego e personalidade sem comprometer a legibilidade ou sobrecarregar a interface.

## 💌 Funcionalidades

### 🏠 1. Página inicial

A tela inicial funciona como a entrada para o espaço do casal.

* Identidade visual D&M.
* Apresentação de David e Malu.
* Seção de momentos e bolhas de histórias.
* Barra de navegação inferior para as principais áreas do aplicativo.

**Estado:** interface inicial implementada; parte da navegação ainda precisa ser conectada às telas definitivas.

### 💬 2. Chat

A conversa é o núcleo funcional do protótipo.

* Mensagens de texto.
* Identificação de quem enviou cada mensagem.
* Horários das mensagens.
* Balões com cores diferentes para cada participante.
* Seletor temporário entre Malu e David para testar os dois lados da conversa.
* Reações com emojis: ❤️ 😂 🥰 😭 👍.
* Seleção de imagens pela galeria.
* Visualização ampliada das fotografias.
* Seleção de arquivos pelo sistema Android.
* Interface para mensagens de áudio.

**Estado:** mensagens, reações e visualização de fotos implementadas no protótipo. A seleção de arquivos também foi adicionada. A gravação e reprodução de áudio ainda precisam de testes e correções.

### 📷 3. Fotografias e mídia

As fotografias são tratadas como parte da conversa, não apenas como anexos externos.

A proposta inclui:

* Escolher imagens da galeria.
* Exibir fotografias diretamente nos balões de mensagem.
* Ampliar uma imagem ao tocar nela.
* Evoluir futuramente para captura de fotos pela câmera.

**Estado:** seleção pela galeria, exibição no chat e ampliação implementadas. Captura pela câmera ainda planejada.

### 📎 4. Compartilhamento de arquivos

O aplicativo possui uma interface para selecionar arquivos usando o seletor nativo do Android.

A experiência planejada inclui documentos PDF, arquivos de texto e outros formatos compatíveis, com nome e identificação visual do anexo.

**Estado:** seleção e apresentação dos anexos implementadas no protótipo. A abertura de diferentes tipos de arquivo e a persistência do acesso precisam ser validadas.

### 🎙️ 5. Mensagens de áudio

O recurso de áudio está em desenvolvimento.

A experiência desejada inclui:

* Iniciar uma gravação pelo microfone.
* Exibir o tempo de gravação.
* Interromper a gravação.
* Inserir o áudio na conversa.
* Reproduzir e pausar o áudio dentro do chat.

A implementação utiliza as APIs nativas `MediaRecorder` e `MediaPlayer`, com solicitação de permissão para acessar o microfone.

**Estado:** implementação inicial realizada; comportamento de gravação e reprodução ainda precisa ser validado em um dispositivo real.

### 🌷 6. Histórias, galeria e perfis

Essas áreas fazem parte da visão do produto e serão desenvolvidas gradualmente.

* **Histórias:** pequenos registros visuais do dia a dia, com possibilidade futura de expiração após 24 horas.
* **Galeria:** coleção organizada de fotografias e vídeos compartilhados.
* **Perfil individual:** foto, informações pessoais e opções de personalização.
* **Perfil do casal:** um espaço conjunto para apresentar a identidade de David e Malu.

**Estado:** funcionalidades planejadas; as interfaces e a navegação correspondentes ainda precisam ser desenvolvidas.

### 📖 7. Memórias e diário compartilhado

Uma evolução futura do D&M é transformar o aplicativo em um arquivo vivo da história do casal.

Possibilidades:

* Diário compartilhado.
* Álbuns por ocasião.
* Linha do tempo de momentos importantes.
* Publicações com texto, imagem, link ou vídeo.
* Organização de lembranças por data.
* Registro de datas especiais.

Esses recursos serão avaliados conforme o avanço do projeto.

---

## 🛠️ Tecnologias utilizadas

| Tecnologia               | Finalidade                                         |
| ------------------------ | -------------------------------------------------- |
| **Kotlin**               | Linguagem principal                                |
| **Jetpack Compose**      | Construção declarativa das interfaces              |
| **Material 3**           | Componentes e estrutura visual                     |
| **Android Studio**       | Ambiente de desenvolvimento                        |
| **Gradle**               | Automação de build e gerenciamento de dependências |
| **Coil 3**               | Carregamento e exibição de imagens                 |
| **MediaRecorder**        | Gravação de áudio                                  |
| **MediaPlayer**          | Reprodução de áudio                                |
| **Activity Result APIs** | Seleção de imagens, arquivos e permissões          |
| **Git e GitHub**         | Controle de versão e hospedagem do código          |

### Configuração técnica atual

* **Package name:** `com.example.dm_davidemalu`
* **Linguagem:** Kotlin
* **Interface:** Jetpack Compose
* **Compile SDK:** 36
* **Target SDK:** 36
* **Minimum SDK:** 24
* **Android Gradle Plugin:** 8.13.2
* **Kotlin:** 2.0.21
* **Compose BOM:** 2024.09.00
* **Coil Compose:** 3.0.4

As versões acima representam a configuração atual de desenvolvimento e poderão mudar conforme as necessidades do projeto.

## 🗂️ Organização do código

A estrutura principal do aplicativo segue uma separação inicial entre telas, componentes reutilizáveis e tema visual.

```text
DMDavideMalu/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       │   └── com/example/dm_davidemalu/
│   │       │       ├── MainActivity.kt
│   │       │       └── ui/
│   │       │           ├── components/
│   │       │           │   └── StoryBubble.kt
│   │       │           ├── screens/
│   │       │           │   ├── HomeScreen.kt
│   │       │           │   └── ChatScreen.kt
│   │       │           └── theme/
│   │       ├── res/
│   │       └── AndroidManifest.xml
│   └── build.gradle.kts
├── gradle/
│   └── libs.versions.toml
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

*Observação: a árvore representa a organização prevista e conhecida do projeto. Alguns arquivos podem estar em outros diretórios ou ser adicionados durante a evolução.*

### Responsabilidades dos principais arquivos

* `MainActivity.kt`: inicializa a aplicação e controla a navegação atual entre as telas.
* `HomeScreen.kt`: contém a interface inicial.
* `ChatScreen.kt`: reúne a interface da conversa e a lógica inicial de mensagens, reações e mídia.
* `StoryBubble.kt`: implementa o componente visual reutilizável para histórias.
* `theme/`: concentra cores e configurações visuais do aplicativo.
* `AndroidManifest.xml`: declara a atividade principal e as permissões necessárias.

A estrutura poderá evoluir para separar a lógica de negócio, os modelos de dados, a persistência e a comunicação com o servidor.

---

## 🚀 Como executar o projeto

### Pré-requisitos

* Android Studio compatível com a configuração do projeto.
* JDK compatível com a configuração Gradle.
* Android SDK 36 instalado.
* Git instalado.
* Um dispositivo Android ou emulador.

### 1. Clonar o repositório

Depois que o repositório estiver publicado no GitHub, execute:

```bash
git clone https://github.com/SEU-USUARIO/DMDavideMalu.git
cd DMDavideMalu
```

Substitua `SEU-USUARIO` pelo nome da conta proprietária do repositório.

### 2. Abrir no Android Studio

Abra a pasta clonada no Android Studio e aguarde a sincronização do Gradle.

### 3. Executar

Conecte um dispositivo Android com a depuração USB habilitada ou inicie um emulador.

Em seguida, selecione a configuração `app` e pressione **Run ▶**.

O primeiro build pode levar mais tempo por causa do download das dependências.

### 4. Permissão de microfone

O recurso de gravação de áudio exige a permissão `RECORD_AUDIO` no `AndroidManifest.xml` e autorização do usuário em tempo de execução.

A permissão deve ser solicitada somente quando o usuário tentar utilizar o recurso.

---

## 🧭 Roadmap de desenvolvimento

O D&M será desenvolvido de maneira incremental, priorizando funcionalidades pequenas, testáveis e que possam ser integradas sem comprometer o que já funciona.

* [x] Criar o projeto Android com Kotlin e Jetpack Compose.
* [x] Definir a identidade visual inicial.
* [x] Criar a página inicial.
* [x] Implementar a navegação inicial para o chat.
* [x] Criar balões de mensagem com identificação do remetente.
* [x] Implementar horários nas mensagens.
* [x] Adicionar reações com emojis.
* [x] Selecionar imagens pela galeria.
* [x] Ampliar imagens dentro do chat.
* [x] Adicionar a seleção inicial de arquivos.
* [ ] Corrigir e validar a gravação de áudio.
* [ ] Validar a reprodução, a pausa e a duração dos áudios.
* [ ] Melhorar o tratamento de erros e as permissões.
* [ ] Implementar persistência local das mensagens e dos anexos.
* [ ] Criar as telas definitivas de galeria e perfil.
* [ ] Desenvolver histórias e publicações compartilhadas.
* [ ] Implementar um backend para comunicação entre dois dispositivos.
* [ ] Sincronizar mensagens e arquivos pela internet.
* [ ] Implementar autenticação e associação segura dos dois participantes.
* [ ] Projetar mecanismos de privacidade, autorização e proteção dos dados.
* [ ] Testar o aplicativo em diferentes dispositivos Android.
* [ ] Preparar uma versão de distribuição.

## 🌐 Próxima grande etapa: comunicação real

O protótipo atual funciona principalmente dentro da execução local do aplicativo. Para que David e Malu conversem em celulares diferentes, mesmo estando longe um do outro, será necessário desenvolver uma arquitetura de comunicação cliente-servidor.

A arquitetura futura poderá incluir:

1. **Aplicativo Android:** interface, composição de mensagens e apresentação de mídia.
2. **Backend:** autenticação, autorização, gerenciamento das conversas e regras de acesso.
3. **Banco de dados:** armazenamento das mensagens, metadados e estados de entrega.
4. **Armazenamento de mídia:** serviço para guardar imagens, documentos e áudios.
5. **Comunicação em tempo real:** entrega de mensagens sem depender de atualizações manuais.
6. **Segurança:** conexões HTTPS, controle de acesso por participante e proteção de credenciais.

A escolha entre construir um backend próprio ou utilizar um serviço gerenciado será feita quando a interface e os fluxos locais estiverem mais estáveis.

**Importante:** até essa etapa, o aplicativo não deve ser considerado um mensageiro funcional pela internet. As mensagens de teste, as imagens e os demais dados ainda não constituem um sistema completo de sincronização entre usuários.

## 🔐 Privacidade e segurança

A proposta do D&M é ser um espaço privado, mas a privacidade precisa ser implementada tecnicamente, não apenas declarada.

Antes de disponibilizar uma versão real, será necessário:

* Restringir o acesso às contas autorizadas.
* Proteger as credenciais e os segredos de configuração.
* Evitar registrar conteúdo privado em logs.
* Validar as permissões de leitura e escrita no backend.
* Definir políticas de retenção e exclusão de arquivos.
* Avaliar criptografia em trânsito e, conforme a arquitetura, proteção dos dados armazenados.
* Considerar criptografia ponta a ponta caso a confidencialidade das mensagens seja um requisito do produto.

O repositório não deve conter senhas, tokens de acesso, chaves privadas, arquivos de assinatura do aplicativo ou informações pessoais desnecessárias.

## 🧪 Testes

O desenvolvimento segue uma abordagem prática: implementar uma funcionalidade, executar o aplicativo, observar seu comportamento e corrigir os problemas antes de avançar.

Os testes devem incluir:

* Navegação entre telas.
* Envio e apresentação de mensagens.
* Seleção e visualização de fotografias.
* Abertura de anexos compatíveis.
* Concessão e recusa da permissão de microfone.
* Gravação e reprodução de áudio.
* Comportamento ao fechar e reabrir o aplicativo.
* Persistência e sincronização, quando implementadas.
* Testes de acesso indevido entre usuários.

## 🤝 Contribuições

Este é um projeto pessoal e experimental, desenvolvido como uma oportunidade de aprendizado em desenvolvimento Android.

Sugestões, relatos de bugs e propostas de melhoria são bem-vindos. Antes de contribuir, consulte a organização do código e evite incluir dados pessoais ou informações privadas nos exemplos, commits e relatórios de problemas.

## 📌 Estado atual

**D&M está em desenvolvimento.**

O foco atual é estabilizar o chat e concluir os recursos locais de mídia antes de avançar para persistência, backend e comunicação pela internet.

O projeto não deve ser utilizado como serviço de mensagens de produção enquanto essas etapas não estiverem concluídas.

## 💜 A ideia por trás do D&M

Este projeto começou com uma vontade simples: construir um cantinho digital que tivesse a identidade de duas pessoas.

Cada tela é uma oportunidade de aprender. Cada erro é uma oportunidade de entender melhor como o software funciona. E cada funcionalidade aproxima a ideia inicial de algo concreto.

O objetivo não é apenas fazer um aplicativo funcionar, mas aprender a projetar, desenvolver, testar e evoluir um produto de software do início ao fim.

**D&M — duas iniciais, um espaço compartilhado e muitas histórias para guardar.**

---

<p align="center">
  Feito com Kotlin, curiosidade e um pouco de 💜.
</p>
