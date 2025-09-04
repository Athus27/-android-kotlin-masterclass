
# Android Kotlin Masterclass — Diário de Aprendizado

> Repositório do meu estudo contínuo de **Desenvolvimento Android** com **Kotlin**, **Android Studio** e **Jetpack Compose**.  
> Cada pasta contém um projeto do curso, com código, anotações e prints/GIFs.

[![Kotlin](https://img.shields.io/badge/Kotlin-1.9+-orange.svg)](#)
[![Android](https://img.shields.io/badge/Android-14-green.svg)](#)
[![Jetpack%20Compose](https://img.shields.io/badge/Jetpack-Compose-blue.svg)](#)
[![Status](https://img.shields.io/badge/Status-Em%20andamento-yellow.svg)](#)

---

## 🗂 Estrutura

```

.
├── Day01\_HelloWorld/
├── Day02\_Variaveis/
├── Day03\_Classes/
├── Day04\_BankAccountApp/
├── Day05\_JetpackCompose/
├── ShoppingListApp/
├── UnitConverter/
├── MyRecipeApp/
├── LocationApp/
├── WishListApp/
├── MusicApp/
├── ChatroomApp\_Firebase/
└── FinalProject\_TrelloClone/

````

> 🔁 Se os nomes/pastas diferirem, ajuste os links da seção **Projetos**.

---

## 🎯 Objetivo

- Consolidar fundamentos de **Kotlin** (funções, classes, coleções, OOP).
- Construir UIs com **XML** e principalmente **Jetpack Compose**.
- Aplicar **arquitetura MVVM**, **State**, **Navigation** e **ViewModel**.
- Integrar **APIs REST** com **Retrofit** e **Coroutines**.
- Persistir dados com **Room** e **SharedPreferences**.
- Usar recursos do dispositivo (GPS, câmera, galeria) e **Maps/Places**.
- Autenticação e dados em **Firebase** (Auth/Firestore/Storage).
- Publicar projetos bem documentados para **portfólio**.

---

## 🚀 Como executar (Android Studio)

1. **Clone** o repositório:
   ```bash
   git clone https://github.com/Athus27/-android-kotlin-masterclass.git
````

2. Abra no **Android Studio** (versão recomendada: Giraffe/Koala+).
3. Sincronize o **Gradle** ➜ `Sync Project`.
4. Escolha um **emulador** ou **dispositivo físico**.
5. `Run ▶` para executar.

> 🔐 Projetos com **API keys** (ex.: Google Maps/Geocoding): crie um `local.properties` ou arquivo `secrets.xml` conforme indicado no README interno do projeto.

---

## 🧩 Tech Stack

* **Kotlin**, **Coroutines/Flow**
* **Jetpack Compose**, **Material 3**, **Navigation**
* **ViewModel**, **LiveData** (quando aplicável), **State Hoisting**
* **Retrofit/OkHttp**, **Gson**
* **Room**, **SharedPreferences**
* **Firebase** (Auth, Firestore, Storage), **FCM** (quando aplicável)
* **Google Maps / Places**
* **Gradle**, **Git/GitHub**

---

## 📚 Progresso (checklist)

* [ ] Fundamentos de Kotlin
* [ ] Android Studio + Emulador
* [ ] Compose básico (Text, Button, Column/Row, State)
* [ ] Listas com **LazyColumn** / **RecyclerView**
* [ ] Navegação entre telas (**Navigation**)
* [ ] MVVM + Repository
* [ ] Consumo de API (**Retrofit**)
* [ ] Persistência local (**Room**)
* [ ] Permissões e **Location**
* [ ] **Firebase Auth/Firestore/Storage**
* [ ] Testes (unitários/instrumentados)
* [ ] Publicação (Play Console)

---

## 📦 Projetos

| Projeto                    | Pasta                       | Tópicos chave                    |
| -------------------------- | --------------------------- | -------------------------------- |
| Hello World / Setup        | `Day01_HelloWorld/`         | Android Studio, Preview          |
| Fundamentos Kotlin         | `Day02_Variaveis/`          | Tipos, if/else, loops            |
| Classes e Data Classes     | `Day03_Classes/`            | OOP, construtores                |
| Bank Account App           | `Day04_BankAccountApp/`     | Listas, lógica                   |
| Jetpack Compose Basics     | `Day05_JetpackCompose/`     | Composables, State               |
| Unit Converter             | `UnitConverter/`            | Compose, State, UI               |
| Shopping List App          | `ShoppingListApp/`          | Compose, Dialog, Lists           |
| My Recipe App (API)        | `MyRecipeApp/`              | Retrofit, JSON, MVVM             |
| Location App               | `LocationApp/`              | Permissões, GPS, Geocoder        |
| Wish List (Room + DI)      | `WishListApp/`              | Room, Repository, DI             |
| Music App (Nav + Scaffold) | `MusicApp/`                 | Navigation, Scaffold             |
| Chatroom (Firebase)        | `ChatroomApp_Firebase/`     | Auth, Firestore                  |
| Trello Clone (Final)       | `FinalProject_TrelloClone/` | Firestore, Storage, Notificações |

> Cada pasta contém um **README próprio** descrevendo objetivos, passos de execução e screenshots.

---

## 📝 Convenção de commits

* `feat:` nova funcionalidade
* `fix:` correção de bug
* `refactor:` melhoria de código/arquitetura
* `docs:` mudanças em documentação
* `chore:` atualização de dependências/config

Ex.:
`feat(wishlist): adicionar criação de item com Room`
`fix(recipe): corrigir NullPointer ao parsear JSON`

---

## 🖼 Screenshots / GIFs

> Adicione imagens em cada projeto (ex.: `docs/screenshot_01.png`) e referencie no README daquele app.

* `ShoppingListApp/docs/preview.gif`
* `MyRecipeApp/docs/categories.png`
* `WishListApp/docs/list.png`

---

## 🗺 Roadmap pessoal

1. Finalizar **Compose + Navigation + MVVM** com 2 apps completos.
2. Integrar **Retrofit** e **Room** em um projeto só (online/offline).
3. Implementar **Firebase Auth** + Firestore em app com CRUD.
4. Escrever **tests** (ViewModel/Repository).
5. Otimizar **README** e **prints** para portfólio (LinkedIn/GitHub).

---

## 🤝 Contribuição

Sinta-se à vontade para abrir **Issues** com dúvidas/ideias ou **PRs** com sugestões de melhoria.

---

## 👤 Autor

**Athus Silva Souza**
GitHub: [@Athus27](https://github.com/Athus27) • Email: [athussilva27@gmail.com](mailto:athussilva27@gmail.com)

