# Problem Matchers for Biu!

## Usage

```json
{
  "version": "2.0.0",
  "tasks": [
    {
      "label": "biu",
      "type": "shell",
      "command": "yarn",
      "args": ["biu"],
      "isBackground": true,
      "group": {
        "kind": "build",
        "isDefault": true
      },
      "problemMatcher": "$biu-typescript"
    }
  ]
}
```
