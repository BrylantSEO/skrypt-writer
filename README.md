# Skrypt Writer

Generator skryptów lekcji i interaktywnych wizualizacji dla kursów online.

## Jak działa

1. **Wpisz klucz OpenRouter API** — potrzebujesz konta na [openrouter.ai](https://openrouter.ai)
2. **Wybierz model** — domyślnie `anthropic/claude-sonnet-4-6`, ale możesz wpisać dowolny model dostępny na OpenRouter
3. **Generuj skrypt** — AI tworzy pełny skrypt lekcji do przeczytania/nagrania
4. **Generuj stronę wizualną** — AI na podstawie skryptu tworzy interaktywną stronę HTML z diagramami, animacjami i wizualizacjami

## Kluczowa cecha

Strona wizualna jest generowana **na podstawie skryptu**, nie niezależnie. Dzięki temu treść prezentacji odpowiada dokładnie temu, co jest w skrypcie.

## Użycie

Otwórz `index.html` w przeglądarce. Wszystko działa lokalnie — dane (klucz API, postęp, wygenerowane treści) zapisywane są w `localStorage`.

## Konfiguracja modeli

Możesz użyć dowolnego modelu dostępnego na OpenRouter, np.:
- `anthropic/claude-sonnet-4-6` (domyślny)
- `anthropic/claude-opus-4-6`
- `google/gemini-2.5-pro`
- `openai/gpt-4o`

Osobne pole na model skryptów i model wizualizacji.

## Technologie

- Vanilla HTML/CSS/JS — zero zależności
- OpenRouter API (streaming)
- Dark theme, responsive

## Licencja

MIT
