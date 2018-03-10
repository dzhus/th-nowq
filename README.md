# th-nowq

[![Travis CI build status](https://travis-ci.org/dzhus/th-nowq.svg)](https://travis-ci.org/dzhus/th-nowq)
[![Hackage](https://img.shields.io/hackage/v/th-nowq.svg?colorB=5e5184&style=flat)](https://hackage.haskell.org/package/th-nowq)
[![Hackage deps](https://img.shields.io/hackage-deps/v/th-nowq.svg)](http://packdeps.haskellers.com/feed?needle=th-nowq)

```haskell
{-# LANGUAGE TemplateHaskell #-}
import Language.Haskell.TH.Now

main :: IO ()
main = print $ "Running app compiled on " ++ $(nowQ)
```
