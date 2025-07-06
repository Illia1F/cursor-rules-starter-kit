# Tailwind CSS Rules & Conventions

This folder contains Tailwind CSS rules and best practices for modern UI development.

> **Important**: This is a starter kit that covers essential Tailwind CSS patterns and conventions. The rules provided in `.cursorrules.mdc` are designed to work with both Tailwind CSS 3.x and 4.x. It does not contain all capabilities of Tailwind CSS 4.x. For comprehensive documentation and advanced features, please refer to the [official Tailwind CSS documentation](https://tailwindcss.com/docs).

## Class Ordering Convention

Always follow this exact order when writing Tailwind classes:

1. Layout → `flex`, `grid`, `absolute`
2. Flexbox/Grid → `items-center`, `justify-between`
3. Spacing → `m-4`, `p-6`, `gap-4`
4. Sizing → `w-full`, `h-64`
5. Typography → `text-lg`, `font-bold`
6. Visual → `bg-blue-500`, `border`, `rounded-lg`
7. Miscellaneous → `cursor-pointer`, `z-10`
8. States → `hover:bg-blue-600`, `focus:ring-2`
9. Responsive → `sm:text-xl`, `md:flex-row`

## Key Rules Applied

- **Mobile-first**: Use `sm:`, `md:`, `lg:`, `xl:` prefixes
- **Typography**: Headings (`font-bold`) → Subheadings (`font-semibold`) → Body (`font-normal`)
- **Colors**: Semantic usage for states (red-error, green-success, blue-info, yellow-warning)
- **Spacing**: Prefer `space-*` and `mt-*` over `mb-*`
- **Accessibility**: Always include `focus:ring-2` and `sr-only` for screen readers
- **Interactions**: Use `group` and `peer` utilities for complex states
- **Components**: Use `@apply` for repeated patterns

See `.cursorrules.mdc` for complete examples and detailed explanations.
