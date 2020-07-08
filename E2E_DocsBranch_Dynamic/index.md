# Test Case 201334: [SEO Validation][Standard]: Verify suggestion reported for duplicated image alt text(TripleColonBlock Syntax)
## 1. Against the rule
:::image type="content" source="./images/pig1.jpg" alt-text="test alt text":::

:::image source="./images/pig2.jpg" alt-text="test alt text":::

## 2. Follow the rule
### 2.1 Unique alt text
:::image source="./images/pig11.jpg" alt-text="unique alt text":::

--------------------------------------------------
Result: 
    "test alt text": 2
