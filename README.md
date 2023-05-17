![Redux](https://v8.ngrx.io/generated/images/guide/store/state-management-lifecycle.png)

## Pasos:

1. Install dependecias 
  - ng add @ngrx/store-devtools 
  - ng add @ngrx/store

2. Modo de uso 
  - en el app.module se debe agregar en imports 
    StoreModule.forRoot({}, {}),
    StoreDevtoolsModule.instrument({ maxAge: 25, logOnly: !isDevMode() })
