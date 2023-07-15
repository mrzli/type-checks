# Type Checks

Runtime type checks.

## Install

```bash
npm install --save @gmjs/type-checks
```

## API

```typescript
function isBoolean(value: unknown): value is boolean;

function isNumber(value: unknown): value is number;

function isString(value: unknown): value is string;

function isDate(value: unknown): value is Date;

function isArray<T = unknown>(value: unknown): value is T[];

function isObject<T extends Record<string | number, any> = Record<string | number, any>>(value: unknown): value is T;
```
