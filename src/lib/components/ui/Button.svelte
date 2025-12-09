<script lang="ts">
  export let variant: 'primary' | 'secondary' | 'outline' | 'ghost' = 'primary';
  export let size: 'sm' | 'md' | 'lg' = 'md';
  export let className = '';
  export let href = '';

  const baseStyles = "inline-flex items-center justify-center font-medium transition-colors focus:outline-none focus:ring-2 focus:ring-offset-2 disabled:opacity-50 disabled:pointer-events-none rounded-full";
  
  const variants = {
    primary: "bg-[#4355FF] text-white hover:bg-[#3b4ce0] focus:ring-[#4355FF]",
    secondary: "bg-gray-100 text-gray-900 hover:bg-gray-200 focus:ring-gray-500",
    outline: "border border-gray-200 bg-transparent hover:bg-gray-100 text-gray-900",
    ghost: "hover:bg-gray-100 text-gray-600 hover:text-gray-900",
  };

  const sizes = {
    sm: "h-8 px-4 text-sm",
    md: "h-10 px-6 text-sm",
    lg: "h-12 px-8 text-base",
  };

  $: classes = `${baseStyles} ${variants[variant]} ${sizes[size]} ${className}`;
</script>

{#if href}
  <a {href} class={classes}>
    <slot />
  </a>
{:else}
  <button class={classes} {...$$restProps}>
    <slot />
  </button>
{/if}
