# Working paper quarto template

## Creating a New Article

To create a new article using this format:

```bash
quarto use template FinYang/wp
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add FinYang/wp
```

Then, add the format to your document options:

```yaml
format:
  wp-pdf: default
```    

## Options

Use the blindable div to hide content that should not show up in the blind version. Use `blind: true` to toggle it in the yaml.


```
::: {.blindable}
Content to hide
:::
```

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

