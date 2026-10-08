```
nix flake show github:nix-ontouchstart/jsonl2md
github:nix-ontouchstart/jsonl2md/1866dc12851966a871ae15aedcae1bf0d3172b6b?narHash=sha256-MlGpFF9IFBwxtI%2BG8nZUJCEUd9M11TmRE6QyNB6HLY8%3D
└───packages
    └───aarch64-linux
        └───default: package 'jsonl2md-0.1.1'
```

```
echo '{"id": "123", "key": "value"}' | nix run github:nix-ontouchstart/jsonl2md --refresh
= id

123

= key

value

---
```
