# Svelte 5 vs Svelte 4 Copilot Instructions

## Key Migration Features
- Use **runes** for advanced reactivity control
- Replace reactive declarations with `$state` and `$derived`
- Upgrade event handlers from `on:` directives to properties
- Migrate from slots to **snippets** for reusable markup
- Implement `$effect` for side effects management

## Svelte 5 New Features

### State Management
- Use `$state()` for reactive state variables
- Use `$derived()` for computed values
- Use `$state.raw()` for non-reactive state when needed
- Replace `let` declarations with `$state` for component state

### Component Props
- Use `$props()` to destructure component props
- Use `$bindable()` for two-way data binding
- Props are automatically reactive in Svelte 5

### Effects and Side Effects
- Use `$effect()` for side effects (replaces `$:` reactive statements)
- Use `$effect.pre()` for effects that run before DOM updates
- Effects automatically track dependencies

### Event Handling
- Replace `on:click={handler}` with `onclick={handler}`
- Remove event modifiers; use wrapper functions instead
- Event handlers are now properties, not directives

### Snippets (Replacing Slots)
- Use `{#snippet name()}...{/snippet}` for reusable markup
- Call snippets with `{@render snippetName()}`
- More flexible than Svelte 4 slots

## Migration Guide

### Before (Svelte 4)
```svelte
<script>
  let count = 0;
  $: doubled = count * 2;
  
  function increment() {
    count += 1;
  }
</script>

<button on:click={increment}>
  Count: {count}, Doubled: {doubled}
</button>
```

### After (Svelte 5)
```svelte
<script>
  let count = $state(0);
  let doubled = $derived(count * 2);
  
  function increment() {
    count += 1;
  }
</script>

<button onclick={increment}>
  Count: {count}, Doubled: {doubled}
</button>
```

## Best Practices
- Use `$state` for all component state that needs reactivity
- Prefer `$derived` over manually managed computed values
- Use `$effect` sparingly; prefer reactive statements when possible
- Test migration incrementally, component by component
- Leverage Svelte 5's improved TypeScript support