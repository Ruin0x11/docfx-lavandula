# docfx-lavandula
A minimalist DocFX template. Based on [MathewSachin/docfx-tmpl](https://github.com/MathewSachin/docfx-tmpl).

![Screenshot](screenshots/1.png)

## Usage

In docfx.json:

```json
{
    "build": {
        "template": [
            "default",
            "docfx-lavandula/src"
        ]
    }
}
```

With the command line:

```
docfx -t default,docfx-lavandula/src
```
