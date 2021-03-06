---
layout: default
title: readjson
published: true
tags: [reference, io functions, functions, readjson, json, container]
---

[%CFEngine_function_prototype(filename, maxbytes)%]

**Description:** Parses JSON data from the first `maxbytes` bytes of
file `filename` and returns the result as a `data` variable.

[%CFEngine_function_attributes(filename, maxbytes)%]

**Example:**

```cf3
    vars:

      "loadthis"

         data =>  readjson("/tmp/data.json", 4000);
```

**See also:** `readdata()`, `parsejson()`, `storejson()`, `parseyaml()`, `readyaml()`, `mergedata()`, and `data` documentation.
