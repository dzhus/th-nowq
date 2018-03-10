# th-nowq

```haskell
{-# LANGUAGE TemplateHaskell #-}
import Language.Haskell.TH.Now

main = print $ "Running app compiled on " ++ $(nowQ)
```
