---
toc: false
---

# Defined Strings V1.3

```js
const raw = await FileAttachment("data/strings.1.3.tsv").tsv();

const query = view(Inputs.search(raw, {
  placeholder: "Search skillList..."
}))
```

```js
view(
    Inputs.table(
        query,
        {width: width,
        rows: 31,
        select: false,
        }
    )
)
```