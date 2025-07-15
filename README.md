## To reproduce
- run `yarn biome format` => it shows errors because of the CRLF line endings
- open `crlf.ts` in VSCode and save the file => nothing happens, the line endings are kept


**So the CLI and VSCode extension do not have the same behaviour**