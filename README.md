# Translate

A basic react app built with the learning goal of understanding react's context system.

steps

- create context `React.createContext('english')`
- create context type in nested child `static contextType = LanguageContext`
- OR by creating a provider i.e. `<LanguageContext.Provider value={this.state.language}>`
- access context via `this.context` for single context in a component
- access with `Consumer` if multiple contexts
- Consumer must be provided with a function