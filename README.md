# TALLER MARKDOWN

## ¿QUÉ ES MARKDOWN?

***Markdown*** es un lenguaje de marcado ligero creado por John Gruber y Aaron Swartz que trata de facilitar la redacción y lectura de documentos en texto plano, utilizando un conjunto de etiquetas muy sencillas para aplicar estilo al documento.


## ENCABEZADOS

#### Sintaxis Github:


  ![Image Encabezados](./images/encabezados.png){ align=center, width="380" }

#### Sintaxis Markdown:

```markdown 
# Taller IESFONTETA 1
## Taller IESFONTETA 2
### Taller IESFONTETA 3
#### Taller IESFONTETA 4
##### Taller IESFONTETA 5
###### Taller IESFONTETA 6
```

## ESTILOS DE TEXTO 


#### Sintaxis Github:
*Texto en cursiva* o _Texto en cursiva_  
**Texto en negrita** o __Texto en negrita__  
~~Texto tachado~~
`Texto en monospace`


#### Sintaxis Markdown:

```markdown 
*Texto en cursiva* o _Texto en cursiva_  
**Texto en negrita** o __Texto en negrita__  
~~Texto tachado~~
`Texto en monospace`
```


## LISTAS



### LISTAS ORDENADAS

#### Sintaxis Github:

1. Primer ítem
2. Segundo ítem
3. Tercer ítem


#### Sintaxis Markdown:

```markdown 
1. Primer ítem
2. Segundo ítem
3. Tercer ítem

```

### LISTAS ORDENADAS ANIDADAS

#### Sintaxis Github:

1. ASIR  
  1.1 ASIR 1  
  1.2 ASIR 2  
2. DAW  
  2.1 DAW 1  
  2.2 DAW 2  
3. C.ESPECI  
4. UNIVERSIDAD


#### Sintaxis Markdown:

```markdown 
1. ASIR  
  1.1 ASIR 1  
  1.2 ASIR 2  
2. DAW  
  2.1 DAW 1  
  2.2 DAW 2  
3. C.ESPECI  
4. UNIVERSIDAD

```

### LISTAS DESORDENADAS 

#### Sintaxis Github:

* Item 1
* Item 2
* Item 3
* Item 4
  
#### Sintaxis Markdown:

```markdown 
* Item 1
* Item 2
* Item 3
* Item 4

```



## ENLACES

#### Sintaxis Github:

[Enlace a Aules](https://portal.edu.gva.es/aules/)

[Enlace a Aules](https://github.com "Ir a AULES")


#### Sintaxis Markdown:

```markdown 

[Enlace a Aules](https://portal.edu.gva.es/aules/)

[Enlace a Aules](https://portal.edu.gva.es/aules/ "Ir a AULES")

```

## IMÁGENES

#### Sintaxis Github:

![SuperMario](./images/supermario.png){ align=center, width="200" }

![Sonic](https://static.wikia.nocookie.net/sonic/images/6/6d/Sonic_67.png){ align=center, width="150" }

#### Sintaxis Markdown:

```markdown 
![SuperMario](./images/supermario.png) { align=center, width="150" }

<!-- enlace de una imagen externa -->
![Sonic](https://static.wikia.nocookie.net/sonic/images/6/6d/Sonic_67.png){ align=center, width="200" }
```



## TABLAS

#### Sintaxis Github:

| Nombre     | Edad | Ciudad     |
|------------|------|------------|
| Emiliano   | 43   | Teruel     |
| Julio      | 31   | Barcelona  |
| Gema       | 29   | Valencia   |
| Salva      | 39   | Valencia   |


#### Sintaxis Markdown:

```markdown 

| Nombre     | Edad | Ciudad     |
|------------|------|------------|
| Emiliano   | 43   | Teruel     |
| Julio      | 31   | Barcelona  |
| Gema       | 29   | Valencia   |
| Salva      | 39   | Valencia   |

```

[Maquetar Tablas](https://tableconvert.com/es/markdown-generator "Ir a Maquetar")


## BLOQUES DE CÓDIGO

#### Sintaxis Github:

##### Java
```java
public class EstructuraRepetitivaFor1 {
    public static void main(String[] ar) {
        int f;
        for(f=1;f<=100;f++) {
            System.out.print(f);
            System.out.print("-");
        }
    }
}
```
##### Javascript
```javascript
   let vec = new Array(10);
        for (let f = 0; f < vec.length; f++) {
            vec[f] = parseInt(Math.random() * 1001);
        }
        let cadena = vec.toString();
        document.write(cadena);


```


#### Sintaxis Markdown:

```markdown 
```java
public class EstructuraRepetitivaFor1 {
    public static void main(String[] ar) {
        int f;
        for(f=1;f<=100;f++) {
            System.out.print(f);
            System.out.print("-");
        }
    }
}

```javascript
   let vec = new Array(10);
        for (let f = 0; f < vec.length; f++) {
            vec[f] = parseInt(Math.random() * 1001);
        }
        let cadena = vec.toString();
        document.write(cadena);


```


```



## CÓDIGO

#### Sintaxis Github:


#### Sintaxis Markdown:

```markdown 



```


## CÓDIGO

#### Sintaxis Github:
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

#### Sintaxis Markdown:

```markdown 



```


BIBLIOGRAFÍA

https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax