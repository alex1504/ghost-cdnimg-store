# Adapter Usage

```sh
mkdir -p content/adapters/storage/ghost-cdnimg-store
cp node_modules/ghost-cdnimg-store/index.js content/adapters/storage/ghost-cdnimg-store/index.js
```

```json
{
  "storage": {
    "active": "ghost-cdnimg-store",
    "ghost-cdnimg-store": {
      "server": ""
    }
  }
}
```
