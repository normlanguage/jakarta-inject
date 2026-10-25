# jakarta.inject Skill

Use this skill to work with Norm module `jakarta.inject` version 8. Use only declarations listed below.

## `jakarta.inject`

Source: `Inject.norm`

### `Inject`

```norm
annotation Inject implements FieldTarget, ConstructorTarget, FunctionTarget, RuntimeRetention, ManagedField
```

## `jakarta.inject`

Source: `Named.norm`

### `Named`

```norm
annotation Named implements PackageTarget, TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, LocalTarget, RuntimeRetention
```

#### `value`

```norm
String value
```

Type: `String`

#### `Named`

```norm
Named(String? value)
```

Parameters:

- `value`: `String?`

## `jakarta.inject`

Source: `Provider.norm`

### `Provider`

```norm
interface Provider<T>
```

Type parameters:

- `T`

#### `get`

```norm
T? get()
```

Returns: `T?`

## `jakarta.inject`

Source: `Qualifier.norm`

### `Qualifier`

```norm
annotation Qualifier implements TypeTarget, RuntimeRetention
```

## `jakarta.inject`

Source: `Scope.norm`

### `Scope`

```norm
annotation Scope implements TypeTarget, RuntimeRetention
```

## `jakarta.inject`

Source: `Singleton.norm`

### `Singleton`

```norm
annotation Singleton implements PackageTarget, TypeTarget, FieldTarget, ConstructorTarget, FunctionTarget, ParameterTarget, LocalTarget, RuntimeRetention
```

