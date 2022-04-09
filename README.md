# README

A collection of snippets from Typescript.

## Release Notes

- `alw` - allow function

```typescript
// $ = place holder
const $func_name = ($arg): $type => {
  $return ; // if $type is `void` or `any`, return is removed.
};
```

- `alw:s` - simple allow function

```typescript
// $ = place holder
const $func_name = ($arg): $type => $expression;
```

- `type:f` - function type declaration with function syntax

```typescript
// $ = place holder
type $type_name = ($arg:$arg_type) => $return_type;
```

- `type:m` - function type declaration with method syntax

```typescript
// $ = place holder
type $type_name = {
  ($arg:$arg_type): $return_type;
};
```

- `fin` - Insert after try-catch statement