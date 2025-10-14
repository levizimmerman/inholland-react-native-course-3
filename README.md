# React Native Course - 3

## Slide decks

- [Theming](https://levizimmerman.github.io/inholland-react-native-course-3/slides/theming.html)
- [Project Structure](https://levizimmerman.github.io/inholland-react-native-course-3/slides/project-structure.html)
- [Dependencies](https://levizimmerman.github.io/inholland-react-native-course-3/slides/dependencies.html)
- [Use of AI](https://levizimmerman.github.io/inholland-react-native-course-3/slides/use-ai.html)


## End Assignment

### Required items
‼️ Check off each item to get a 5.5 grade. Implement optional items to get a higher grade.

#### App functionality

- [ ] Working Expo Go project, should be able to scan the QR code and see the app running on any device.
- [ ] PokeAPI is used to fetch Pokemon data https://pokeapi.co/
  - [ ] List of Pokemon is loaded from the API.
  - [ ] Pokemon details (metadata, stats, evolution chain) are loaded from the API.
- [ ] List of Pokemon is displayed in a FlatList.
  - [ ] Must be able to filter the list by name using the search bar.
- [ ] Pokemon details are displayed in a ScrollView.
  - [ ] Must be able to navigate to the Pokemon details page from the list.
  - [ ] Must be able to favorite the Pokemon.
  - [ ] Must display type(s) for the Pokemon and use a unique color for each type.
  - [ ] Pokemon detail tabs should be swipeable left and right.
- [ ] Favorites list is displayed in a FlatList.
  - [ ] Must be able to navigate to the Pokemon details page from the favorites list.
  - [ ] Must be able to unfavorite the Pokemon.
  - [ ] Empty state must be displayed when there are no favorites.
- [ ] Pokemon actions must include:
    - [ ] Favorite.
    - [ ] Share.
    - [ ] Open in detail view.
- [ ] All async operations must include an loading and error state.
    - [ ] Fetching Pokemon list.
    - [ ] Fetching Pokemon details.
    - [ ] Fetching Pokemon evolution chain.

#### Project setup
- [ ] Tanstack Query for API calls.
- [ ] Expo Router for navigation.
- [ ] SQLite for local storage.
- [ ] Uses Typescript with no TS errors.
- [ ] Uses ESLint with no ESLint errors. (ideally use [React Compiler Linter](https://docs.expo.dev/guides/react-compiler/#enabling-the-linter))
- [ ] Uses Separation of Concerns (determine a project structure that follows this principle).
- [ ] Expo Font is used to implement [the font](./assets/fonts.zip).


### Optional items
Each optional item is worth 1 extra point.

- [ ] Use of animations (e.g. loading in UI elements).
- [ ] Dark mode support (making use of theming).
- [ ] Pokemon list is paginated and infinite scroll is used.
- [ ] Clean Typescript: no use of `any`, typecasting `as SomeType`, or TS ignore comments.
- [ ] Pixel Perfect Design on either iOS or Android.
- [ ] No bugs, console errors and use of console.log.
- [ ] Added [localizations](https://docs.expo.dev/guides/localization/) for the app.
- [ ] Adds Pokémon Battle Feature.

## References
Useful links to read up on:
- [Bulletproof React](https://github.com/alan2207/bulletproof-react)
- [Vertical Slice Architecture](https://antondevtips.com/blog/vertical-slice-architecture-the-best-ways-to-structure-your-project)
- [Expo SDKs](https://docs.expo.dev/versions/latest/sdk/accelerometer/)
- [React Native Directory](https://reactnative.directory/)
- [Clean Code Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
- [Example React Native App Codebases](https://github.com/kelset/react-native-community-map?tab=readme-ov-file#-open-source-apps)
- [Bike Shedding](https://thedecisionlab.com/biases/bikeshedding)
- [Tailwind Example Theming Variables](https://tailwindcss.com/docs/theme)
- [From 1+1 in Assembly to LLMs: The Evolution of Computing Abstraction](https://taewoon.kim/2024-11-12-1+1/)
- [Measuring Abstraction Level of Languages](https://github.com/const/const-articles/blob/main/evolution/2025/01-measuring-language-level/MeasuringAbstractionLevelOfLanguages.adoc)