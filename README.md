# new-react-component-cli

## Installation

```bash
$ npm install -g fractureinc/new-react-component-cli#v2.5.9
```

## Usage

```bash
$ new-component Button
```

Your project will now have a new directory at `src/components/Button` with generated files:

```
src
└── components
    └── Button
        ├── Button.fixtures.tsx
        ├── Button.stories.tsx
        ├── Button.style.tsx
        ├── Button.test.tsx
        ├── Button.tsx
        └── index.tsx
```

> The `index.tsx` allows you to `import` from the directory (eg. `import Button from 'components/Button'`), while having `Button.tsx` means that you're never lost in a sea of `index.tsx` files in your editor.
