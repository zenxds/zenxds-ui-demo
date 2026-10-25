# Third-party notices

## shadcn.io demo color references

As of 0.2.1, Supabase, Claude and Catppuccin semantic colors match the live palette controls on these demo pages, captured on 2026-10-25:

- https://www.shadcn.io/theme/supabase
- https://www.shadcn.io/theme/claude
- https://www.shadcn.io/theme/catppuccin

The exact light/dark numeric palette snapshots are recorded in test/fixtures/shadcn-io-colors.json. Colors are mapped to scoped --zen-* variables. No demo page implementation, fonts, images or layout is copied. These are community presets, not official product themes or endorsements.

## tweakcn radius adaptation

Source: https://github.com/jnsahaj/tweakcn/blob/a3b47b37cba97dd637de517aab52c45ec0f83456/utils/theme-presets.ts

Project: https://github.com/jnsahaj/tweakcn

The original 0.2.0 presets in src/styles/skins.css were adapted from tweakcn contributors' work, licensed under Apache-2.0. Version 0.2.1 replaces their semantic colors with the demo references above and retains the radius adaptation. The license is included in licenses/tweakcn-Apache-2.0.txt.

Modifications: translated semantic colors into scoped --zen-* variables; retained system fonts, current component layout, shadows and status palette; mapped radius to the existing component radius variables. These community presets are not official product themes or endorsements.

The original shadcn license remains in LICENSE.
