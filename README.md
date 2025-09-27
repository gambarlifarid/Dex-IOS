# Dex – Pokédex App (Swift 6, Core Data, PokeAPI)

An iOS app that fetches and stores Pokémon data locally, allowing users to browse, search, and favorite Pokémon in a Pokédex.

## Features
- **Fetch Pokémon**: Retrieves the first 151 Pokémon from the [PokeAPI](https://pokeapi.co).
- **Core Data storage**: Pokémon data is persisted locally, including types, stats, and sprites.
- **Favorites**: Swipe to mark Pokémon as favorite and filter by favorites.
- **Search**: Search Pokémon by name with live filtering.
- **UI**: Displays sprites, shiny versions, types (with colored badges), and stats in a modern SwiftUI interface.

## Tech Stack
- Swift 6
- SwiftUI
- Core Data (local persistence)
- Async/Await with URLSession
- JSON decoding with custom Decodable models
- MVVM-style data flow
