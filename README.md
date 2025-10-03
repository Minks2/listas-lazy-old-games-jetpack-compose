# Projeto Fundamentos de Jetpack Compose: Listas e Filtros

Este é um projeto acadêmico para a disciplina de desenvolvimento mobile, focado em demonstrar os conceitos fundamentais do Jetpack Compose, a moderna toolkit de UI do Android. O aplicativo exibe uma lista de jogos e seus respectivos estúdios, permitindo a filtragem dinâmica dos dados.

## Integrantes da Equipe

- Nome: Caio Sales - RM:552286
- Nome:Cintia Cristina Braga Angelo - RM:552253
- Nome: Guilherme Bussolan - RM:552455
- Nome: Henrique Mosseri - RM:552240


##  Estrutura do Projeto
```
app/
 ├── src/
 │   ├── main/
 │   │   ├── java/
 │   │   │   └── carreiras/com/github/fundamentos_jetpack_compose_listas_lazy/
 │   │   │        ├── MainActivity.kt         # Tela principal e lógica de UI
 │   │   │        ├── components/
 │   │   │        │    ├── GameCard.kt       # Componente visual para jogos
 │   │   │        │    └── StudioCard.kt     # Componente visual para estúdios
 │   │   │        ├── model/
 │   │   │        │    └── Game.kt           # Modelo de dados para jogos
 │   │   │        ├── repository/
 │   │   │        │    ├── GameRepository.kt # Funções de acesso e filtro de dados
 │   │   │        │    └── ...
 │   │   │        └── ui/theme/              # Temas e estilos
 │   │   └── res/                            # Recursos (layouts, strings, etc)
 │   └── ...
 └── ...
```

## Funcionalidades Implementadas

-   **Listagem de Estúdios:** Exibição de uma lista horizontal (`LazyRow`) com os estúdios de desenvolvimento.
-   **Listagem de Jogos:** Exibição de uma lista vertical (`LazyColumn`) com os jogos.
-   **Filtro por Texto:** Um campo de texto permite ao usuário buscar jogos por nome ou por estúdio.
-   **Filtro por Clique:** Ao clicar em um card de estúdio na lista horizontal, a lista de jogos é automaticamente filtrada para exibir apenas os jogos daquele estúdio.
-   **Limpar Filtro:** Um botão de texto ("Limpar filtro") aparece sempre que um filtro está ativo, permitindo ao usuário retornar à lista completa com um único clique.

## Telas (Screenshots)

**Instrução:** Tire prints da sua aplicação e substitua os links abaixo. Você pode arrastar as imagens para a área de edição do `README.md` no site do GitHub que ele gera o link para você.

#### Tela Principal (Sem Filtro)
![Tela Principal](https://via.placeholder.com/300x600.png?text=Cole+aqui+o+print+da+tela+inicial)

#### Tela com Filtro por Texto
![Filtro por Texto](https://via.placeholder.com/300x600.png?text=Cole+aqui+o+print+filtrando+por+texto)

#### Tela com Filtro por Clique no Estúdio
![Filtro por Clique](https://via.placeholder.com/300x600.png?text=Cole+aqui+o+print+filtrando+por+clique)

## Tecnologias Utilizadas

-   **Linguagem:** Kotlin
-   **Toolkit de UI:** Jetpack Compose
-   **Arquitetura:** MV (Model-View) simples para fins didáticos
-   **IDE:** Android Studio

## Como funciona

- A tela principal exibe uma lista de jogos e uma lista horizontal de estúdios.
- O usuário pode filtrar os jogos digitando o nome do estúdio ou clicando em um StudioCard.
- O filtro pode ser limpo facilmente com o botão "Limpar filtro".

## Como rodar o projeto

1. Clone este repositório:
   ```sh
   git clone <url-do-repositorio>
   ```
2. Abra o projeto no Android Studio.
3. Execute em um emulador ou dispositivo físico Android.



---


