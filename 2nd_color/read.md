# Changing Text Underline Color in Tailwind CSS

To change the underline color of text in Tailwind CSS, you can use the `decoration-{color}` utility class. Here are some examples:

```html
<!-- Basic underline color -->
<p class="underline decoration-red-500">Red underline</p>
<p class="underline decoration-blue-600">Blue underline</p>
<p class="underline decoration-green-400">Green underline</p>

<!-- Combining with other underline utilities -->
<p class="underline decoration-2 decoration-purple-500">Thicker purple underline</p>
<p class="underline decoration-wavy decoration-yellow-400">Wavy yellow underline</p>
```

## Available Options

- Use any Tailwind color: `decoration-{color}-{shade}`
- Adjust thickness: `decoration-{1|2|4|8}`
- Change style: `decoration-{solid|double|dotted|dashed|wavy}`

You can also customize colors in your `tailwind.config.js` file for custom underline colors.

shading  starting to 50 and end in 950 