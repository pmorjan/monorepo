# monorepo
Example of multiple independent components in a single repository.

To build all components with a single command:
```
go build  -o ./dist/ ./...
```

```
.
├── cmd            // independent components
│   ├── foo
│   ├── bar
│   └── baz
│
├── dist           // compiled binaries
│   ├── foo
│   ├── bar
│   └── baz
│
└── pkg            // shared packages
    └── boo
```
