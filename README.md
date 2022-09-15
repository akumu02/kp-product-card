# kp-product-card

Este es un paquete de pruebas de despliegue en NPM

### Fernando Herrera

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'kp-product-card';
```

```
<ProductCard
        key={product.id}
        product={product}
        initialValues={{
          count: 4,
          // maxCount: 10,
        }}
      >
        {({ reset, maxCount, isMaxCountReached, count, increaseBy }) => (
          <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />
          </>
        )}
</ProductCard>
```
