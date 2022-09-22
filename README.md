# lit_dream component

This ⚡ [Lightning component](lightning.ai) ⚡ was generated automatically with:

```bash
lightning init component lit_dream
```

## To run lit_dream

First, install lit_dream (warning: this component has not been officially approved on the lightning gallery):

```bash
lightning install component https://github.com/theUser/lit_dream
```

Once the app is installed, use it in an app:

```python
from lit_dream import TemplateComponent
import lightning as L


class LitApp(L.LightningFlow):
    def __init__(self) -> None:
        super().__init__()
        self.lit_dream = TemplateComponent()

    def run(self):
        print("this is a simple Lightning app to verify your component is working as expected")
        self.lit_dream.run()


app = L.LightningApp(LitApp())
```
