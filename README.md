# Calculadora Python

Una calculadora simple implementada en Python que permite realizar operaciones básicas.

## Características

- Operaciones disponibles: `suma`, `resta`, `multiplicación`, `división`
- Código limpio y modular

## Instalación

Clona el repositorio:

```bash
git clone https://github.com/tomySinCodigo/calculadora-tutorial-gh.git
cd calculadora-tutorial-gh
```

## API Reference

| Parametros | Tipo     | Descripcion                |
| :-------- | :------- | :------------------------- |
| `a` | `float` | puede ser entero o float |
| `b` | `float` | puede ser entero o float |

### Operaciones

- [sumar](#sumar)
- [restar](#restar)
- [multiplicar](#multiplicar)
- [dividir](#dividir)

---

#### sumar

```bash
sumar(a, b)
```

toma dos numeros y retorna la suma

#### restar

```bash
restar(a, b)
```

toma dos numeros y retorna la resta

#### multiplicar

```bash
multiplicar(a, b)
```

toma dos numeros y retorna la multiplicacion

#### dividir

```bash
dividir(a, b)
```

toma dos numeros y retorna la division

> [!IMPORTANT]  
> **Division por cero**  
> En caso de que el parametro `b` sea cero, la funcion retorna `None` y muestra un `print` con mensaje de error.


agregue una linea, para hacer una prueba