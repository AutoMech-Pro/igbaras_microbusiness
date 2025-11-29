# igbaras_microbusiness
igbaras iloilo microbusiness
Key Layout & Naming Fixes:

Smart Label Wrapping: Enhanced the JavaScript logic to force line breaks on long axis labels (specifically for the Profitability Chart) so they don't get cut off or clutter the view.

Flowchart Alignment: completely rebuilt the "Golden Bean" flowchart using a more robust Flexbox/Grid hybrid structure. The arrows and text now align perfectly on both mobile (vertical stack) and desktop (horizontal flow).

Chart Spacing: Added specific layout padding to Chart.js configurations to prevent axis labels from clipping against the edges of the cards.

3D Plot Readability: Adjusted the Plotly text position to top center with a slight offset to ensure data point names don't obscure the markers.
