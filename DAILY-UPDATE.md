# Daily stock update

The Pink Lady site has a fixed layout. For each new arrival, update only `latest.json`; you do not need to rewrite the webpage.

Use this template:

```json
{
  "date": "NEW • 1 SEPTEMBER 2026",
  "title": "ชื่อสินค้า",
  "text": "สี / จุดเด่น / รายละเอียดสั้น ๆ",
  "url": "#contact",
  "image": "stock/2026-09-01-product.jpg"
}
```

Add the product photograph to a `stock` folder beside `index.html`, then use its filename in `image`. Leave `image` blank when there is no photo yet.

Keep the entry limited to the product, confirmed price and key details. Do not add unconfirmed stock or delivery promises.
