# hab-Product-Card

Este es un paquete de pruebas de desliegue en NPM


### Hugo Ballesteros

## Ejemplo
```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'hab-product-card'
```

```
<ProductCard 
    product={ product }
    initialValues={{
        count: 4,
        maxCount: 10,
    }}
>
    {
        ( { reset, isMaxCountReached, count, increaseBy, maxCount } ) => (
            <>
                <ProductImage />
                <ProductTitle  />
                <ProductButtons />
            </>
        ) 
    }
</ProductCard>
```