## Outline
- How to set common fields used by all models (and why you'd want to do this)
- Initializing Supabase. Using that DB for local dev right now because it's easy and explorable.

## Changelog
- Introduced `dotenv` package to manage env locally. 

## Gotchyas
- Got this error: "Transforming const to the configured target environment ("es5") is not supported yet". [The Fix](https://github.com/drizzle-team/drizzle-orm/issues/803) was to change `compilerOptions` in `tsconfig.json`


## On Deck