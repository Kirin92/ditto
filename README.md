# Ditto

This repository contains a copy of the JSON data generated from [PokeAPI](https://github.com/PokeAPI/pokeapi). I use this to test [PokeKotlin](https://github.com/PokeAPI/pokekotlin) without spamming the live API on every test. All data is pulled automatically from PokeAPI, which is based on [Veekun's data](https://github.com/veekun/pokedex). The included `pulldata` script can be used to update the data with the command `rm -r ./api && ./pulldata http://pokeapi.co ./`. **Please don't use this to hammer PokeAPI!** I recommend calling a local instance of the API: `rm -r ./api && ./pulldata http://localhost:8000 ./` once you have PokeAPI running on your local machine.
