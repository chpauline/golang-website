---
title: UncalledBuiltin
layout: article
---
<!-- Copyright 2023 The Go Authors. All rights reserved.
     Use of this source code is governed by a BSD-style
     license that can be found in the LICENSE file. -->

<!-- Code generated by generrordocs.go; DO NOT EDIT. -->

```
UncalledBuiltin occurs when a built-in function is used as a
function-valued expression, instead of being called.

Per the spec:
 "The built-in functions do not have standard Go types, so they can only
 appear in call expressions; they cannot be used as function values."

Example:
 var _ = copy
```

