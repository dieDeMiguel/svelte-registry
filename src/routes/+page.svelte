<script lang="ts">
  import { Button } from "$lib/components/ui/button/index.js";
</script>

<div class="container mx-auto p-8 space-y-8">
  <div class="space-y-4">
    <h1 class="text-4xl font-bold">Welcome to shadcn-svelte!</h1>
    <p class="text-lg text-muted-foreground">
      Your SvelteKit project is now set up with shadcn-svelte components.
    </p>
  </div>

  <div class="space-y-6">
    <div class="space-y-4">
      <h2 class="text-2xl font-semibold">Button Variants</h2>
      <div class="flex flex-wrap gap-4">
        <Button>Default</Button>
        <Button variant="destructive">Destructive</Button>
        <Button variant="outline">Outline</Button>
        <Button variant="secondary">Secondary</Button>
        <Button variant="ghost">Ghost</Button>
        <Button variant="link">Link</Button>
      </div>
    </div>

    <div class="space-y-4">
      <h2 class="text-2xl font-semibold">Button Sizes</h2>
      <div class="flex flex-wrap items-center gap-4">
        <Button size="sm">Small</Button>
        <Button size="default">Default</Button>
        <Button size="lg">Large</Button>
        <Button size="icon">🚀</Button>
      </div>
    </div>

    <div class="space-y-4">
      <h2 class="text-2xl font-semibold">Interactive Examples</h2>
      <div class="flex flex-wrap gap-4">
        <Button on:click={() => alert('Hello from shadcn-svelte!')}>
          Click me!
        </Button>
        <Button variant="outline" disabled>
          Disabled
        </Button>
      </div>
    </div>
  </div>

  <div class="mt-8 p-4 bg-muted rounded-lg">
    <p class="text-sm text-muted-foreground">
      Visit <a href="https://www.shadcn-svelte.com/" class="underline hover:text-foreground">shadcn-svelte.com</a> 
      to explore more components and documentation.
    </p>
  </div>
</div>
