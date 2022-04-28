#Reag-product-card 

Este es un paquete de pruebas de despliegue en NPM

### Ramiro Eduardo Alvizo Gamez


##Ejemplo

```
<ProductCard product={ product } initialValues={{ count: 4, maxCount: 10 }}>
          {
            ( { reset, count, isMaxCountReached, maxCount, increaseBy } ) => (
            <>
              <ProductImage />
              <ProductTitle title={""}/>
              <ProductButtons/>
            </>
            )
          }
        </ProductCard>
```