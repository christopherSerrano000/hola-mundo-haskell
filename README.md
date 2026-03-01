# hola-mundo-haskell

Un programa básico en Haskell que imprime "Hola, mundo!" en la consola.

## Requisitos

Tener instalado [GHC](https://www.haskell.org/ghc/) (Glasgow Haskell Compiler).

## Cómo correrlo

**Compilar y ejecutar:**

```bash
ghc main.hs -o hola
./hola
```

## Notas

- `module Main where` declara el módulo principal del programa.
- `main :: IO ()` indica que `main` es una acción de entrada/salida que no retorna ningún valor útil.
- `putStrLn` imprime una cadena seguida de un salto de línea.
