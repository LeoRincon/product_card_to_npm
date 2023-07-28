# Product_Card_to_npm

This is a repository of example to publish a component in npm, of the course React Pro by Fernando Herrera.

## Example

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'product_card_to_npm';
```

```
<ProductCard
    product={ product }
    initialValues={{
        count: 6,
        maxCount: 10,
    }}
>
    {
        ({ reset, count, isMaxCountReached, maxCount, increaseBy  }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
```
